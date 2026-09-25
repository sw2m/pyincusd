# SystemProvider


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | [**SystemProviderConfig**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemProviderConfig.md) |  | [optional] 
**state** | [**SystemProviderState**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemProviderState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_provider import SystemProvider

# TODO update the JSON string below
json = "{}"
# create an instance of SystemProvider from a JSON string
system_provider_instance = SystemProvider.from_json(json)
# print the JSON string representation of the object
print(SystemProvider.to_json())

# convert the object into a dict
system_provider_dict = system_provider_instance.to_dict()
# create an instance of SystemProvider from a dict
system_provider_from_dict = SystemProvider.from_dict(system_provider_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


