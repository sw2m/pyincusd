# SystemLogging


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | [**SystemLoggingConfig**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemLoggingConfig.md) |  | [optional] 
**state** | **object** |  | [optional] 

## Example

```python
from pyincusd.models.system_logging import SystemLogging

# TODO update the JSON string below
json = "{}"
# create an instance of SystemLogging from a JSON string
system_logging_instance = SystemLogging.from_json(json)
# print the JSON string representation of the object
print(SystemLogging.to_json())

# convert the object into a dict
system_logging_dict = system_logging_instance.to_dict()
# create an instance of SystemLogging from a dict
system_logging_from_dict = SystemLogging.from_dict(system_logging_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


