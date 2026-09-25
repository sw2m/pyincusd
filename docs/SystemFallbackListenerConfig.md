# SystemFallbackListenerConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**listen_address** | **str** |  | [optional] 
**persistent** | **bool** |  | [optional] 
**trusted_client_certificates** | **List[str]** |  | [optional] 

## Example

```python
from pyincusd.models.system_fallback_listener_config import SystemFallbackListenerConfig

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFallbackListenerConfig from a JSON string
system_fallback_listener_config_instance = SystemFallbackListenerConfig.from_json(json)
# print the JSON string representation of the object
print(SystemFallbackListenerConfig.to_json())

# convert the object into a dict
system_fallback_listener_config_dict = system_fallback_listener_config_instance.to_dict()
# create an instance of SystemFallbackListenerConfig from a dict
system_fallback_listener_config_from_dict = SystemFallbackListenerConfig.from_dict(system_fallback_listener_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


