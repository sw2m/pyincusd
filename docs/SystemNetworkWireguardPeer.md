# SystemNetworkWireguardPeer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allowed_ips** | **List[str]** |  | [optional] 
**endpoint** | **str** |  | [optional] 
**persistent_keepalive** | **int** |  | [optional] 
**preshared_key** | **str** |  | [optional] 
**public_key** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_wireguard_peer import SystemNetworkWireguardPeer

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkWireguardPeer from a JSON string
system_network_wireguard_peer_instance = SystemNetworkWireguardPeer.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkWireguardPeer.to_json())

# convert the object into a dict
system_network_wireguard_peer_dict = system_network_wireguard_peer_instance.to_dict()
# create an instance of SystemNetworkWireguardPeer from a dict
system_network_wireguard_peer_from_dict = SystemNetworkWireguardPeer.from_dict(system_network_wireguard_peer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


