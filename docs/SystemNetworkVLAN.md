# SystemNetworkVLAN


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**addresses** | **List[str]** |  | [optional] 
**firewall_rules** | [**List[SystemNetworkFirewallRule]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkFirewallRule.md) |  | [optional] 
**id** | **int** |  | [optional] 
**mtu** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**parent** | **str** |  | [optional] 
**required_for_online** | **str** |  | [optional] 
**roles** | **List[str]** |  | [optional] 
**routes** | [**List[SystemNetworkRoute]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkRoute.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_network_vlan import SystemNetworkVLAN

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkVLAN from a JSON string
system_network_vlan_instance = SystemNetworkVLAN.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkVLAN.to_json())

# convert the object into a dict
system_network_vlan_dict = system_network_vlan_instance.to_dict()
# create an instance of SystemNetworkVLAN from a dict
system_network_vlan_from_dict = SystemNetworkVLAN.from_dict(system_network_vlan_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


