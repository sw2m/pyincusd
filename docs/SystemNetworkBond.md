# SystemNetworkBond


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**addresses** | **List[str]** |  | [optional] 
**bridge** | [**SystemNetworkBridge**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemNetworkBridge.md) |  | [optional] 
**ethernet** | [**SystemNetworkEthernet**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemNetworkEthernet.md) |  | [optional] 
**firewall_rules** | [**List[SystemNetworkFirewallRule]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemNetworkFirewallRule.md) |  | [optional] 
**hwaddr** | **str** |  | [optional] 
**lldp** | **bool** |  | [optional] 
**members** | **List[str]** |  | [optional] 
**mode** | **str** |  | [optional] 
**mtu** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**options** | [**SystemNetworkBondOptions**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemNetworkBondOptions.md) |  | [optional] 
**required_for_online** | **str** |  | [optional] 
**roles** | **List[str]** |  | [optional] 
**routes** | [**List[SystemNetworkRoute]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemNetworkRoute.md) |  | [optional] 
**vlan_tags** | **List[int]** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_bond import SystemNetworkBond

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkBond from a JSON string
system_network_bond_instance = SystemNetworkBond.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkBond.to_json())

# convert the object into a dict
system_network_bond_dict = system_network_bond_instance.to_dict()
# create an instance of SystemNetworkBond from a dict
system_network_bond_from_dict = SystemNetworkBond.from_dict(system_network_bond_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


