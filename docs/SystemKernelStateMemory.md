# SystemKernelStateMemory


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**zram_swap** | [**SystemKernelStateMemoryZramSwap**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemKernelStateMemoryZramSwap.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_state_memory import SystemKernelStateMemory

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelStateMemory from a JSON string
system_kernel_state_memory_instance = SystemKernelStateMemory.from_json(json)
# print the JSON string representation of the object
print(SystemKernelStateMemory.to_json())

# convert the object into a dict
system_kernel_state_memory_dict = system_kernel_state_memory_instance.to_dict()
# create an instance of SystemKernelStateMemory from a dict
system_kernel_state_memory_from_dict = SystemKernelStateMemory.from_dict(system_kernel_state_memory_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


