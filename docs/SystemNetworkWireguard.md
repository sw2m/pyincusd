# SystemNetworkWireguard


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**addresses** | **List[str]** |  | [optional] 
**firewall_rules** | [**List[SystemNetworkFirewallRule]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkFirewallRule.md) |  | [optional] 
**mtu** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**peers** | [**List[SystemNetworkWireguardPeer]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkWireguardPeer.md) |  | [optional] 
**port** | **int** |  | [optional] 
**private_key** | **str** |  | [optional] 
**required_for_online** | **str** |  | [optional] 
**roles** | **List[str]** |  | [optional] 
**routes** | [**List[SystemNetworkRoute]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkRoute.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_network_wireguard import SystemNetworkWireguard

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkWireguard from a JSON string
system_network_wireguard_instance = SystemNetworkWireguard.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkWireguard.to_json())

# convert the object into a dict
system_network_wireguard_dict = system_network_wireguard_instance.to_dict()
# create an instance of SystemNetworkWireguard from a dict
system_network_wireguard_from_dict = SystemNetworkWireguard.from_dict(system_network_wireguard_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


