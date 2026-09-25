# SystemUpdateConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auto_reboot** | **bool** |  | [optional] 
**channel** | **str** |  | [optional] 
**check_frequency** | **str** |  | [optional] 
**maintenance_windows** | [**List[SystemUpdateMaintenanceWindow]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemUpdateMaintenanceWindow.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_update_config import SystemUpdateConfig

# TODO update the JSON string below
json = "{}"
# create an instance of SystemUpdateConfig from a JSON string
system_update_config_instance = SystemUpdateConfig.from_json(json)
# print the JSON string representation of the object
print(SystemUpdateConfig.to_json())

# convert the object into a dict
system_update_config_dict = system_update_config_instance.to_dict()
# create an instance of SystemUpdateConfig from a dict
system_update_config_from_dict = SystemUpdateConfig.from_dict(system_update_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


