# SystemNetworkWireguardState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**listening_port** | **int** |  | [optional] 
**peers** | [**List[SystemNetworkWireguardPeerState]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkWireguardPeerState.md) |  | [optional] 
**public_key** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_wireguard_state import SystemNetworkWireguardState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkWireguardState from a JSON string
system_network_wireguard_state_instance = SystemNetworkWireguardState.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkWireguardState.to_json())

# convert the object into a dict
system_network_wireguard_state_dict = system_network_wireguard_state_instance.to_dict()
# create an instance of SystemNetworkWireguardState from a dict
system_network_wireguard_state_from_dict = SystemNetworkWireguardState.from_dict(system_network_wireguard_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


