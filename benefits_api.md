Verifying submission:


[Datadog Dashboard](https://vagov.ddog-gov.com/dashboard/4d8-3fn-dbp/benefits-intake-form-submission-tracking?fromUser=false&refresh_mode=sliding&view=spans&from_ts=1717772535566&to_ts=1718377335566&live=true)


```ruby
uuid = SavedClaim::Form210779.find(1).form_submissions.last.form_submission_attempts.last.benefits_intake_uuid
```

```bash
curl -X GET 'https://sandbox-api.va.gov/services/vba_documents/v1/uploads/0631c920-e3b0-4792-86b5-29ad009bf174/download' \
--header 'accept: application/zip' --header 'apikey: MY_API_KEY' -o test.zip
```
response:  a zip with filled pdf and metadata.json

```JSON
{"veteranFirstName":"John","veteranLastName":"Doe","fileNumber":"123456789","zipCode":"62701","source":"SavedClaim::Form210779 va.gov","docType":"21-0779","businessLine":"CMP"}
```


```bash
curl -X GET 'https://sandbox-api.va.gov/services/vba_documents/v1/uploads/0631c920-e3b0-4792-86b5-29ad009bf174' \
--header 'accept: application/json' --header 'apikey: MY_API_KEY'
```

```JSON
{
    "data": {
        "id": "0631c920-e3b0-4792-86b5-29ad009bf174",
        "type": "document_upload",
        "attributes": {
            "guid": "0631c920-e3b0-4792-86b5-29ad009bf174",
            "status": "received",
            "code": null,
            "detail": "",
            "final_status": false,
            "updated_at": "2025-11-18T22:02:14.752Z",
            "uploaded_pdf": {
                "total_documents": 1,
                "total_pages": 2,
                "content": {
                    "page_count": 2,
                    "dimensions": {
                        "height": 11,
                        "width": 8.5,
                        "oversized_pdf": false
                    },
                    "file_size": 1557076,
                    "attachments": []
                },
                "line_of_business": "CMP"
            }
        }
    }
}
```