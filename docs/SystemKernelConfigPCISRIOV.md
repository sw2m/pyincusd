# SystemKernelConfigPCISRIOV


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pci_address** | **str** |  | [optional] 
**vf_count** | **int** |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_config_pcisriov import SystemKernelConfigPCISRIOV

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelConfigPCISRIOV from a JSON string
system_kernel_config_pcisriov_instance = SystemKernelConfigPCISRIOV.from_json(json)
# print the JSON string representation of the object
print(SystemKernelConfigPCISRIOV.to_json())

# convert the object into a dict
system_kernel_config_pcisriov_dict = system_kernel_config_pcisriov_instance.to_dict()
# create an instance of SystemKernelConfigPCISRIOV from a dict
system_kernel_config_pcisriov_from_dict = SystemKernelConfigPCISRIOV.from_dict(system_kernel_config_pcisriov_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


