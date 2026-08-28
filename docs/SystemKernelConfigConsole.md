# SystemKernelConfigConsole


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**baud_rate** | **int** |  | [optional] 
**device** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_config_console import SystemKernelConfigConsole

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelConfigConsole from a JSON string
system_kernel_config_console_instance = SystemKernelConfigConsole.from_json(json)
# print the JSON string representation of the object
print(SystemKernelConfigConsole.to_json())

# convert the object into a dict
system_kernel_config_console_dict = system_kernel_config_console_instance.to_dict()
# create an instance of SystemKernelConfigConsole from a dict
system_kernel_config_console_from_dict = SystemKernelConfigConsole.from_dict(system_kernel_config_console_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


