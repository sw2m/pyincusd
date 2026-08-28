# SystemNetworkBridge


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**disable_multicast_snooping** | **bool** |  | [optional] 
**stp** | **bool** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_bridge import SystemNetworkBridge

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkBridge from a JSON string
system_network_bridge_instance = SystemNetworkBridge.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkBridge.to_json())

# convert the object into a dict
system_network_bridge_dict = system_network_bridge_instance.to_dict()
# create an instance of SystemNetworkBridge from a dict
system_network_bridge_from_dict = SystemNetworkBridge.from_dict(system_network_bridge_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


