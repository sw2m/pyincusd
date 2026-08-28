# SystemKernelConfigNetwork


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**buffer_size** | **int** |  | [optional] 
**netdev_max_backlog** | **int** |  | [optional] 
**queuing_discipline** | **str** |  | [optional] 
**tcp_congestion_algorithm** | **str** |  | [optional] 
**tcp_mtu_probing** | **bool** |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_config_network import SystemKernelConfigNetwork

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelConfigNetwork from a JSON string
system_kernel_config_network_instance = SystemKernelConfigNetwork.from_json(json)
# print the JSON string representation of the object
print(SystemKernelConfigNetwork.to_json())

# convert the object into a dict
system_kernel_config_network_dict = system_kernel_config_network_instance.to_dict()
# create an instance of SystemKernelConfigNetwork from a dict
system_kernel_config_network_from_dict = SystemKernelConfigNetwork.from_dict(system_kernel_config_network_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


