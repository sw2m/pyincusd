# SystemPower


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | [**SystemPowerConfig**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemPowerConfig.md) |  | [optional] 
**state** | [**SystemPowerState**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemPowerState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_power import SystemPower

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPower from a JSON string
system_power_instance = SystemPower.from_json(json)
# print the JSON string representation of the object
print(SystemPower.to_json())

# convert the object into a dict
system_power_dict = system_power_instance.to_dict()
# create an instance of SystemPower from a dict
system_power_from_dict = SystemPower.from_dict(system_power_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


