# SystemKernel


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | [**SystemKernelConfig**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemKernelConfig.md) |  | [optional] 
**state** | [**SystemKernelState**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemKernelState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel import SystemKernel

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernel from a JSON string
system_kernel_instance = SystemKernel.from_json(json)
# print the JSON string representation of the object
print(SystemKernel.to_json())

# convert the object into a dict
system_kernel_dict = system_kernel_instance.to_dict()
# create an instance of SystemKernel from a dict
system_kernel_from_dict = SystemKernel.from_dict(system_kernel_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


