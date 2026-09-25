# SystemNetworkInterface


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**addresses** | **List[str]** |  | [optional] 
**bridge** | [**SystemNetworkBridge**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkBridge.md) |  | [optional] 
**ethernet** | [**SystemNetworkEthernet**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkEthernet.md) |  | [optional] 
**firewall_rules** | [**List[SystemNetworkFirewallRule]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkFirewallRule.md) |  | [optional] 
**hwaddr** | **str** |  | [optional] 
**lldp** | **bool** |  | [optional] 
**mtu** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**required_for_online** | **str** |  | [optional] 
**roles** | **List[str]** |  | [optional] 
**routes** | [**List[SystemNetworkRoute]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkRoute.md) |  | [optional] 
**strict_hwaddr** | **bool** |  | [optional] 
**vlan_tags** | **List[int]** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_interface import SystemNetworkInterface

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkInterface from a JSON string
system_network_interface_instance = SystemNetworkInterface.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkInterface.to_json())

# convert the object into a dict
system_network_interface_dict = system_network_interface_instance.to_dict()
# create an instance of SystemNetworkInterface from a dict
system_network_interface_from_dict = SystemNetworkInterface.from_dict(system_network_interface_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


