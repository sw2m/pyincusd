# SystemKernelConfigPCIPassthrough


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pci_address** | **str** |  | [optional] 
**product_id** | **str** |  | [optional] 
**vendor_id** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_config_pci_passthrough import SystemKernelConfigPCIPassthrough

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelConfigPCIPassthrough from a JSON string
system_kernel_config_pci_passthrough_instance = SystemKernelConfigPCIPassthrough.from_json(json)
# print the JSON string representation of the object
print(SystemKernelConfigPCIPassthrough.to_json())

# convert the object into a dict
system_kernel_config_pci_passthrough_dict = system_kernel_config_pci_passthrough_instance.to_dict()
# create an instance of SystemKernelConfigPCIPassthrough from a dict
system_kernel_config_pci_passthrough_from_dict = SystemKernelConfigPCIPassthrough.from_dict(system_kernel_config_pci_passthrough_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


