# SystemNetworkState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**configuration_in_process** | **bool** |  | [optional] 
**interfaces** | [**Dict[str, SystemNetworkInterfaceState]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemNetworkInterfaceState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_network_state import SystemNetworkState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkState from a JSON string
system_network_state_instance = SystemNetworkState.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkState.to_json())

# convert the object into a dict
system_network_state_dict = system_network_state_instance.to_dict()
# create an instance of SystemNetworkState from a dict
system_network_state_from_dict = SystemNetworkState.from_dict(system_network_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


