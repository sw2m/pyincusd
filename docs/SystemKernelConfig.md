# SystemKernelConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**blacklist_modules** | **List[str]** |  | [optional] 
**console** | [**List[SystemKernelConfigConsole]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemKernelConfigConsole.md) |  | [optional] 
**cpu** | [**SystemKernelConfigCPU**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemKernelConfigCPU.md) |  | [optional] 
**memory** | [**SystemKernelConfigMemory**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemKernelConfigMemory.md) |  | [optional] 
**network** | [**SystemKernelConfigNetwork**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemKernelConfigNetwork.md) |  | [optional] 
**pci** | [**SystemKernelConfigPCI**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemKernelConfigPCI.md) |  | [optional] 
**zfs** | [**SystemKernelConfigZFS**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemKernelConfigZFS.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_config import SystemKernelConfig

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelConfig from a JSON string
system_kernel_config_instance = SystemKernelConfig.from_json(json)
# print the JSON string representation of the object
print(SystemKernelConfig.to_json())

# convert the object into a dict
system_kernel_config_dict = system_kernel_config_instance.to_dict()
# create an instance of SystemKernelConfig from a dict
system_kernel_config_from_dict = SystemKernelConfig.from_dict(system_kernel_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


