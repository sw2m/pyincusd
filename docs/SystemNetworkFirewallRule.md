# SystemNetworkFirewallRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**port** | **int** |  | [optional] 
**protocol** | **str** |  | [optional] 
**source** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_firewall_rule import SystemNetworkFirewallRule

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkFirewallRule from a JSON string
system_network_firewall_rule_instance = SystemNetworkFirewallRule.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkFirewallRule.to_json())

# convert the object into a dict
system_network_firewall_rule_dict = system_network_firewall_rule_instance.to_dict()
# create an instance of SystemNetworkFirewallRule from a dict
system_network_firewall_rule_from_dict = SystemNetworkFirewallRule.from_dict(system_network_firewall_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


