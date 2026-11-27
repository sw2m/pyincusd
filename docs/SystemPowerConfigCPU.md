# SystemPowerConfigCPU


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**energy_performance_preference** | **str** |  | [optional] 
**scaling_governor** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_power_config_cpu import SystemPowerConfigCPU

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPowerConfigCPU from a JSON string
system_power_config_cpu_instance = SystemPowerConfigCPU.from_json(json)
# print the JSON string representation of the object
print(SystemPowerConfigCPU.to_json())

# convert the object into a dict
system_power_config_cpu_dict = system_power_config_cpu_instance.to_dict()
# create an instance of SystemPowerConfigCPU from a dict
system_power_config_cpu_from_dict = SystemPowerConfigCPU.from_dict(system_power_config_cpu_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


