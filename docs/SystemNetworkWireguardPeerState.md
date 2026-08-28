# SystemNetworkWireguardPeerState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allowed_ips** | **List[str]** |  | [optional] 
**endpoint** | **str** |  | [optional] 
**latest_handshake** | **str** |  | [optional] 
**persistent_keepalive** | **str** |  | [optional] 
**public_key** | **str** |  | [optional] 
**stats** | [**SystemNetworkInterfaceStats**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemNetworkInterfaceStats.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_network_wireguard_peer_state import SystemNetworkWireguardPeerState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkWireguardPeerState from a JSON string
system_network_wireguard_peer_state_instance = SystemNetworkWireguardPeerState.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkWireguardPeerState.to_json())

# convert the object into a dict
system_network_wireguard_peer_state_dict = system_network_wireguard_peer_state_instance.to_dict()
# create an instance of SystemNetworkWireguardPeerState from a dict
system_network_wireguard_peer_state_from_dict = SystemNetworkWireguardPeerState.from_dict(system_network_wireguard_peer_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


