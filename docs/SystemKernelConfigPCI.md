# SystemKernelConfigPCI


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**passthrough** | [**List[SystemKernelConfigPCIPassthrough]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemKernelConfigPCIPassthrough.md) |  | [optional] 
**sriov** | [**List[SystemKernelConfigPCISRIOV]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemKernelConfigPCISRIOV.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_config_pci import SystemKernelConfigPCI

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelConfigPCI from a JSON string
system_kernel_config_pci_instance = SystemKernelConfigPCI.from_json(json)
# print the JSON string representation of the object
print(SystemKernelConfigPCI.to_json())

# convert the object into a dict
system_kernel_config_pci_dict = system_kernel_config_pci_instance.to_dict()
# create an instance of SystemKernelConfigPCI from a dict
system_kernel_config_pci_from_dict = SystemKernelConfigPCI.from_dict(system_kernel_config_pci_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


