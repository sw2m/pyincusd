# SystemProviderConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **Dict[str, str]** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_provider_config import SystemProviderConfig

# TODO update the JSON string below
json = "{}"
# create an instance of SystemProviderConfig from a JSON string
system_provider_config_instance = SystemProviderConfig.from_json(json)
# print the JSON string representation of the object
print(SystemProviderConfig.to_json())

# convert the object into a dict
system_provider_config_dict = system_provider_config_instance.to_dict()
# create an instance of SystemProviderConfig from a dict
system_provider_config_from_dict = SystemProviderConfig.from_dict(system_provider_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


