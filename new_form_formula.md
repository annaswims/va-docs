# New Form Formula - WIP

- [ ] Make a subclass of [SavedClaim](../vets-api/app/models/saved_claim.rb) `vets-api/app/models/saved_claim/form9999.rb`
```ruby
class SavedClaim::Form9999 < SavedClaim
  FORM = '9999' 
end

```
* [ ] Make a subclass of [ClaimsBaseController](../vets-api/app/controllers/claims_base_controller.rb) `V0::Form9999Controller` `vets-api/app/controllers/v0/form9999_controller.rb` 
  - [ ] Add `service_tag` -> 'my-app-desciption' # I guess we just make it up?
  - [ ] Add `short_name` -> 'form9999' # used for stats key and filtered_params
  - [ ] Add `claim_class`
  - [ ] stub the submit response with 
  ```ruby
    def create
      render json: SavedClaimSerializer.new(SavedClaim::Form9999.new)
    end
  ```


     `confirmation_number` and `guid`  are always the same

- [ ] Document the endpoints in app/swagger/swagger
  -  We use Swagger 2.0 https://swagger.io/specification/v2/ 
  -  We use https://github.com/fotinakis/swagger-blocks 
  - [ ] Add your swagger in ../vets-api/app/swagger/swagger/requests/my_topic.rb 
  - [ ] Make sure to use things like `extend Swagger::Responses::ValidationError` for common error responses
  - [ ] Reference your JSON Schema in your Swagger docs (now or probably later)
  - [ ] use `extend Swagger::Responses::SavedForm` for SavedClaim responses
  - [ ] Add your swagger class to SWAGGERED_CLASSES in app/controllers/v0/apidocs_controller.rb
  - [ ] 