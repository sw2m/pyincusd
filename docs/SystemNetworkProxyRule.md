# SystemNetworkProxyRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination** | **str** |  | [optional] 
**target** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_proxy_rule import SystemNetworkProxyRule

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkProxyRule from a JSON string
system_network_proxy_rule_instance = SystemNetworkProxyRule.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkProxyRule.to_json())

# convert the object into a dict
system_network_proxy_rule_dict = system_network_proxy_rule_instance.to_dict()
# create an instance of SystemNetworkProxyRule from a dict
system_network_proxy_rule_from_dict = SystemNetworkProxyRule.from_dict(system_network_proxy_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


