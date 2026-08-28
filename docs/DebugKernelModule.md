# DebugKernelModule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dependencies** | **List[str]** |  | [optional] 
**in_use** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.debug_kernel_module import DebugKernelModule

# TODO update the JSON string below
json = "{}"
# create an instance of DebugKernelModule from a JSON string
debug_kernel_module_instance = DebugKernelModule.from_json(json)
# print the JSON string representation of the object
print(DebugKernelModule.to_json())

# convert the object into a dict
debug_kernel_module_dict = debug_kernel_module_instance.to_dict()
# create an instance of DebugKernelModule from a dict
debug_kernel_module_from_dict = DebugKernelModule.from_dict(debug_kernel_module_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


