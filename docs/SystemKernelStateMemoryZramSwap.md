# SystemKernelStateMemoryZramSwap

Reported sizes are in bytes.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**compressed_size** | **int** |  | [optional] 
**compression_ratio** | **float** |  | [optional] 
**disk_size** | **int** |  | [optional] 
**incompressed_size** | **int** |  | [optional] 
**total_memory_use** | **int** |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_state_memory_zram_swap import SystemKernelStateMemoryZramSwap

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelStateMemoryZramSwap from a JSON string
system_kernel_state_memory_zram_swap_instance = SystemKernelStateMemoryZramSwap.from_json(json)
# print the JSON string representation of the object
print(SystemKernelStateMemoryZramSwap.to_json())

# convert the object into a dict
system_kernel_state_memory_zram_swap_dict = system_kernel_state_memory_zram_swap_instance.to_dict()
# create an instance of SystemKernelStateMemoryZramSwap from a dict
system_kernel_state_memory_zram_swap_from_dict = SystemKernelStateMemoryZramSwap.from_dict(system_kernel_state_memory_zram_swap_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


