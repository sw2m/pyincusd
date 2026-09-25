# SystemKernelState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**memory** | [**SystemKernelStateMemory**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemKernelStateMemory.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_state import SystemKernelState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelState from a JSON string
system_kernel_state_instance = SystemKernelState.from_json(json)
# print the JSON string representation of the object
print(SystemKernelState.to_json())

# convert the object into a dict
system_kernel_state_dict = system_kernel_state_instance.to_dict()
# create an instance of SystemKernelState from a dict
system_kernel_state_from_dict = SystemKernelState.from_dict(system_kernel_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


