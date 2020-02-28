# Create Patient Record
This API call permits the application to create new `ehrId`. 

```{
  "_type": "EHR_STATUS",
  "subject": {
    "external_ref": {
      "id": {
        "_type": "GENERIC_ID",
        "value": "ins01",
        "scheme": "id_scheme"
      },
      "namespace": "ehr_craft",
      "type": "PERSON"
    }
  },
  "other_details": {
    "_type": "ITEM_TREE",
    "items": []
  },
  "is_modifiable": "true",
  "is_queryable": "true"
}
```