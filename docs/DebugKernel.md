# DebugKernel


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**architecture** | **str** |  | [optional] 
**cpu_baseline** | **str** |  | [optional] 
**modules** | [**List[DebugKernelModule]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/DebugKernelModule.md) |  | [optional] 
**version** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.debug_kernel import DebugKernel

# TODO update the JSON string below
json = "{}"
# create an instance of DebugKernel from a JSON string
debug_kernel_instance = DebugKernel.from_json(json)
# print the JSON string representation of the object
print(DebugKernel.to_json())

# convert the object into a dict
debug_kernel_dict = debug_kernel_instance.to_dict()
# create an instance of DebugKernel from a dict
debug_kernel_from_dict = DebugKernel.from_dict(debug_kernel_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


