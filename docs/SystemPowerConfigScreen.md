# SystemPowerConfigScreen


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**blank_timeout** | **int** |  | [optional] 

## Example

```python
from pyincusd.models.system_power_config_screen import SystemPowerConfigScreen

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPowerConfigScreen from a JSON string
system_power_config_screen_instance = SystemPowerConfigScreen.from_json(json)
# print the JSON string representation of the object
print(SystemPowerConfigScreen.to_json())

# convert the object into a dict
system_power_config_screen_dict = system_power_config_screen_instance.to_dict()
# create an instance of SystemPowerConfigScreen from a dict
system_power_config_screen_from_dict = SystemPowerConfigScreen.from_dict(system_power_config_screen_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


