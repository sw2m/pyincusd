# SystemKernelConfigCPU


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scaling_governor** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_config_cpu import SystemKernelConfigCPU

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelConfigCPU from a JSON string
system_kernel_config_cpu_instance = SystemKernelConfigCPU.from_json(json)
# print the JSON string representation of the object
print(SystemKernelConfigCPU.to_json())

# convert the object into a dict
system_kernel_config_cpu_dict = system_kernel_config_cpu_instance.to_dict()
# create an instance of SystemKernelConfigCPU from a dict
system_kernel_config_cpu_from_dict = SystemKernelConfigCPU.from_dict(system_kernel_config_cpu_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


