# SystemPowerState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cpu** | [**SystemPowerStateCPU**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemPowerStateCPU.md) |  | [optional] 
**screen** | [**SystemPowerStateScreen**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemPowerStateScreen.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_power_state import SystemPowerState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPowerState from a JSON string
system_power_state_instance = SystemPowerState.from_json(json)
# print the JSON string representation of the object
print(SystemPowerState.to_json())

# convert the object into a dict
system_power_state_dict = system_power_state_instance.to_dict()
# create an instance of SystemPowerState from a dict
system_power_state_from_dict = SystemPowerState.from_dict(system_power_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


