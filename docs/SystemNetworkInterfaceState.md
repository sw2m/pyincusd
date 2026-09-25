# SystemNetworkInterfaceState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**addresses** | **List[str]** |  | [optional] 
**hwaddr** | **str** |  | [optional] 
**lacp** | [**SystemNetworkLACPState**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkLACPState.md) |  | [optional] 
**lldp** | [**List[SystemNetworkLLDPState]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkLLDPState.md) |  | [optional] 
**members** | [**Dict[str, SystemNetworkInterfaceState]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkInterfaceState.md) |  | [optional] 
**mtu** | **int** |  | [optional] 
**roles** | **List[str]** |  | [optional] 
**routes** | [**List[SystemNetworkRoute]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkRoute.md) |  | [optional] 
**speed** | **str** |  | [optional] 
**state** | **str** |  | [optional] 
**stats** | [**SystemNetworkInterfaceStats**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkInterfaceStats.md) |  | [optional] 
**type** | **str** |  | [optional] 
**wireguard** | [**SystemNetworkWireguardState**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkWireguardState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_network_interface_state import SystemNetworkInterfaceState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkInterfaceState from a JSON string
system_network_interface_state_instance = SystemNetworkInterfaceState.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkInterfaceState.to_json())

# convert the object into a dict
system_network_interface_state_dict = system_network_interface_state_instance.to_dict()
# create an instance of SystemNetworkInterfaceState from a dict
system_network_interface_state_from_dict = SystemNetworkInterfaceState.from_dict(system_network_interface_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


