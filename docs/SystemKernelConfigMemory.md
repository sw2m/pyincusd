# SystemKernelConfigMemory


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**persistent_hugepages** | **int** |  | [optional] 
**zram_swap_size** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_config_memory import SystemKernelConfigMemory

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelConfigMemory from a JSON string
system_kernel_config_memory_instance = SystemKernelConfigMemory.from_json(json)
# print the JSON string representation of the object
print(SystemKernelConfigMemory.to_json())

# convert the object into a dict
system_kernel_config_memory_dict = system_kernel_config_memory_instance.to_dict()
# create an instance of SystemKernelConfigMemory from a dict
system_kernel_config_memory_from_dict = SystemKernelConfigMemory.from_dict(system_kernel_config_memory_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


