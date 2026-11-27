# SystemPowerConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cpu** | [**SystemPowerConfigCPU**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemPowerConfigCPU.md) |  | [optional] 
**screen** | [**SystemPowerConfigScreen**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemPowerConfigScreen.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_power_config import SystemPowerConfig

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPowerConfig from a JSON string
system_power_config_instance = SystemPowerConfig.from_json(json)
# print the JSON string representation of the object
print(SystemPowerConfig.to_json())

# convert the object into a dict
system_power_config_dict = system_power_config_instance.to_dict()
# create an instance of SystemPowerConfig from a dict
system_power_config_from_dict = SystemPowerConfig.from_dict(system_power_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


