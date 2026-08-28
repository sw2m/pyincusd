# SystemLoggingSyslog


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** |  | [optional] 
**log_format** | **str** |  | [optional] 
**protocol** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_logging_syslog import SystemLoggingSyslog

# TODO update the JSON string below
json = "{}"
# create an instance of SystemLoggingSyslog from a JSON string
system_logging_syslog_instance = SystemLoggingSyslog.from_json(json)
# print the JSON string representation of the object
print(SystemLoggingSyslog.to_json())

# convert the object into a dict
system_logging_syslog_dict = system_logging_syslog_instance.to_dict()
# create an instance of SystemLoggingSyslog from a dict
system_logging_syslog_from_dict = SystemLoggingSyslog.from_dict(system_logging_syslog_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


