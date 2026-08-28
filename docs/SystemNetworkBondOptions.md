# SystemNetworkBondOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**arp_interval** | **int** |  | [optional] 
**arp_ip_targets** | **List[str]** |  | [optional] 
**down_delay** | **int** |  | [optional] 
**lacp_rate** | **str** |  | [optional] 
**mii_monitor_interval** | **int** |  | [optional] 
**transmit_hash_policy** | **str** |  | [optional] 
**up_delay** | **int** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_bond_options import SystemNetworkBondOptions

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkBondOptions from a JSON string
system_network_bond_options_instance = SystemNetworkBondOptions.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkBondOptions.to_json())

# convert the object into a dict
system_network_bond_options_dict = system_network_bond_options_instance.to_dict()
# create an instance of SystemNetworkBondOptions from a dict
system_network_bond_options_from_dict = SystemNetworkBondOptions.from_dict(system_network_bond_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


