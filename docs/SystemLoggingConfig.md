# SystemLoggingConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**journal_upload** | [**SystemLoggingJournalUpload**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemLoggingJournalUpload.md) |  | [optional] 
**syslog** | [**SystemLoggingSyslog**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemLoggingSyslog.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_logging_config import SystemLoggingConfig

# TODO update the JSON string below
json = "{}"
# create an instance of SystemLoggingConfig from a JSON string
system_logging_config_instance = SystemLoggingConfig.from_json(json)
# print the JSON string representation of the object
print(SystemLoggingConfig.to_json())

# convert the object into a dict
system_logging_config_dict = system_logging_config_instance.to_dict()
# create an instance of SystemLoggingConfig from a dict
system_logging_config_from_dict = SystemLoggingConfig.from_dict(system_logging_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


