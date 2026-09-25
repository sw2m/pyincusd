# SystemLoggingJournalUpload


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tls_ca_certificate** | **str** |  | [optional] 
**tls_client_certificate** | **str** |  | [optional] 
**tls_client_key** | **str** |  | [optional] 
**url** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_logging_journal_upload import SystemLoggingJournalUpload

# TODO update the JSON string below
json = "{}"
# create an instance of SystemLoggingJournalUpload from a JSON string
system_logging_journal_upload_instance = SystemLoggingJournalUpload.from_json(json)
# print the JSON string representation of the object
print(SystemLoggingJournalUpload.to_json())

# convert the object into a dict
system_logging_journal_upload_dict = system_logging_journal_upload_instance.to_dict()
# create an instance of SystemLoggingJournalUpload from a dict
system_logging_journal_upload_from_dict = SystemLoggingJournalUpload.from_dict(system_logging_journal_upload_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


