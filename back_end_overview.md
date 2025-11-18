# Staring a new form on VA.gov

## Back End Overview
### vets-website will post a form to `/v0/form9999`

`V0::Form9999Controller`
The body will have the structure:
```json
{"form":  "{\"key\":\"value\"}" }
```
Yes, the typical pattern is that the form value is not JSON, but stringified json, like This is odd, but the default pattern because of the `X-Key-Inflection` that transforms json keys. (see TOD0 #1 below)

For forms that have have documentation already you can view the API docs at [http://localhost:3000/v0/swagger](<http://localhost:3000/v0/swagger/index.html?urls.primaryName=VA.gov%20Swagger%20Docs%20(v2)>) or [https://dev-api.va.gov/v0/swagger/index.html](https://dev-api.va.gov/v0/swagger/index.html)

### The controller will create and validate new SavedClaim  
<details>
<summary>Slim FormController example:</summary>

```ruby 
claim = SavedClaim::Form9999.new(form: params[:form])
unless claim.save # if not valid
    raise Common::Exceptions::ValidationErrors, claim  #see "Error Handling" below
end
claim.process_attachments! # this is poorly named, it iterates through attachments (file uploads created while someone was filling out the form)

#TODO: delete in-progress form data after submit
```
</details>

If the claim is valid, a `SavedClaimSerializer.new(claim)` object will be returned.
<details>
<summary>Example SavedClaimSerializer response</summary>

```json
    {
    "data": {
        "id": "1",
        "type": "saved_claims",
        "attributes": {
            "submitted_at": "2025-11-11T13:48:31.198Z",
            "regional_office": [],
            "confirmation_number": "76ef8dfe-73b6-414f-91a7-9628fbd2daa0",
            "guid": "76ef8dfe-73b6-414f-91a7-9628fbd2daa0",
            "form": "21-0779"
        }
    }
}
```
</details>

#### Validations

The `claim.form` data must be present, a string (not JSON) and valid against the schema.

The default schema location is  `VetsJsonSchema::SCHEMAS[form_id]`, but can be overridden with `form_schema` in `SavedClaim::Form9999`. The schema should be valid. 

### Submission

  The controller calls `claim.process_attachments!` process_attachments is a bad name for what's happening. 
  It essentially just enqueues a job with: 

````ruby
  Lighthouse::SubmitBenefitsIntakeClaim.perform_async(id)
````

We should think about a synchronous version if we want to immediately return the url with the pdf. Maybe?
````ruby
  Lighthouse::SubmitBenefitsIntakeClaim.new.perform(id)
````

spec/support/vcr_cassettes/accredited_representative_portal/sidekiq/accredited_representative_portal/
Lighthouse::SubmitBenefitsIntakeClaim

To make requests to the lighthouse sandbox locally you need a sandbox key.  The sandbox APIkey process is automated and you get a key as soon as you fill out this form. https://developer.va.gov/explore/api/benefits-intake/sandbox-access 

Then add to Settings.local.yml:
````yaml
benefits_intake_service:
  api_key: APIKEY
````

If you are enqueuing a background job, make sure to have Sidekiq running. You can start Sidekiq with `bundle exec sidekiq` or a variety of other ways in the docs.

Lighthouse::SubmitBenefitsIntakeClaim#generate_metadata makes the bold assumption that `claim.parsed_form` has the following attributes: 
```ruby
{
    veteranFullName: {
        first: "", 
        last: ""
    }
    vaFileNumber: "", # either vaFileNumber OR veteranSocialSecurityNumber if file number is null
    veteranSocialSecurityNumber: "",
    claimantAddress: {postalCode: ""}, 
    veteranAddress: {postalCode: ""}, # veteranAddress is claimantAddress is null
}

```

You can see the file uploaded in vets-api/tmp/ - As a convenience, uploads files aren't deleted in non-production environments

Next to look into: 
ClaimsBaseController#show does this:
````ruby
    submission = CentralMailSubmission.joins(:central_mail_claim).find_by(saved_claims: { guid: params[:id] })
    render json: BenefitsIntakeSubmissionSerializer.new(submission)
````
 or `it 'submits the saved claim successfully' do` for what the output of the job is.

## Error Handling
If you do something like: 
```ruby
raise Common::Exceptions::ValidationErrors, claim unless claim.save
```

The result is a claim.form_submissions
You will get a response of:
<details>
<summary>Example Error response</summary>


```json
{
    "errors": [
        {
            "title": "/veteraninformation/fullname/first value at `/veteranInformation/fullName/first` is not a string",
            "detail": "/veteran-information/full-name/first - value at `/veteranInformation/fullName/first` is not a string",
            "code": "100",
            "source": {
                "pointer": "data/attributes//veteran-information/full-name/first"
            },
            "status": "422"
        }
    ]
}
```
</details>

If you raise something that inherits from `Common::Exceptions::BaseError` (for example, there are many more) the exception will be rescued in [exception_handling.rb](../vets-api/app/controllers/concerns/exception_handling.rb) with: `rescue_from`. It will then, log the error (see: `report_mapped_exception`) and the appropriate JSON response (with the proper response status)[](../vets-api/lib/common/exceptions/validation_errors.rb).

## Schemas
Nearly all form schemas use 
  {"$schema": "http://json-schema.org/draft-04/schema#"}

see [Schema Links](../va-docs/README.md#schema-links)

## Form Submission Status
[Display Form Status for a non-Lighthouse Benefits Intake API Form](../vets-api/lib/forms/submission_statuses/README.md)

## Testing
https://depo-platform-documentation.scrollhelp.site/developer-docs/vcr-debugging
