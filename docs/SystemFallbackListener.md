# SystemFallbackListener

SystemFallbackListener defines a struct to configure the fallback HTTPS listener that will activate if the primary application fails to start, ensuring that basic API connectivity to the system isn't lost.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | [**SystemFallbackListenerConfig**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemFallbackListenerConfig.md) |  | [optional] 
**state** | [**SystemFallbackListenerState**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemFallbackListenerState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_fallback_listener import SystemFallbackListener

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFallbackListener from a JSON string
system_fallback_listener_instance = SystemFallbackListener.from_json(json)
# print the JSON string representation of the object
print(SystemFallbackListener.to_json())

# convert the object into a dict
system_fallback_listener_dict = system_fallback_listener_instance.to_dict()
# create an instance of SystemFallbackListener from a dict
system_fallback_listener_from_dict = SystemFallbackListener.from_dict(system_fallback_listener_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


