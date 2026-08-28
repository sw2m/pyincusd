# SystemNetworkInterfaceStats


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rx_bytes** | **int** |  | [optional] 
**rx_errors** | **int** |  | [optional] 
**tx_bytes** | **int** |  | [optional] 
**tx_errors** | **int** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_interface_stats import SystemNetworkInterfaceStats

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkInterfaceStats from a JSON string
system_network_interface_stats_instance = SystemNetworkInterfaceStats.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkInterfaceStats.to_json())

# convert the object into a dict
system_network_interface_stats_dict = system_network_interface_stats_instance.to_dict()
# create an instance of SystemNetworkInterfaceStats from a dict
system_network_interface_stats_from_dict = SystemNetworkInterfaceStats.from_dict(system_network_interface_stats_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


