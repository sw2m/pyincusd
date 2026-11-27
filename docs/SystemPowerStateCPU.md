# SystemPowerStateCPU


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**energy_performance_available_preferences** | **List[str]** |  | [optional] 
**energy_performance_preference** | **str** |  | [optional] 
**scaling_available_governors** | **List[str]** |  | [optional] 
**scaling_driver** | **str** |  | [optional] 
**scaling_governor** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_power_state_cpu import SystemPowerStateCPU

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPowerStateCPU from a JSON string
system_power_state_cpu_instance = SystemPowerStateCPU.from_json(json)
# print the JSON string representation of the object
print(SystemPowerStateCPU.to_json())

# convert the object into a dict
system_power_state_cpu_dict = system_power_state_cpu_instance.to_dict()
# create an instance of SystemPowerStateCPU from a dict
system_power_state_cpu_from_dict = SystemPowerStateCPU.from_dict(system_power_state_cpu_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


