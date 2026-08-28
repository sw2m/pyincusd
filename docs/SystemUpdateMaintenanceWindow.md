# SystemUpdateMaintenanceWindow

StartDayOfWeek and EndDayOfWeek are optional, and if non-zero can be used to limit the migration window to certain day(s).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**end_day_of_week** | **str** | Weekday defines our own type. The time package&#39;s Weekday doesn&#39;t include any way to indicate an empty value, which we need. | [optional] 
**end_hour** | **int** |  | [optional] 
**end_minute** | **int** |  | [optional] 
**start_day_of_week** | **str** | Weekday defines our own type. The time package&#39;s Weekday doesn&#39;t include any way to indicate an empty value, which we need. | [optional] 
**start_hour** | **int** |  | [optional] 
**start_minute** | **int** |  | [optional] 

## Example

```python
from pyincusd.models.system_update_maintenance_window import SystemUpdateMaintenanceWindow

# TODO update the JSON string below
json = "{}"
# create an instance of SystemUpdateMaintenanceWindow from a JSON string
system_update_maintenance_window_instance = SystemUpdateMaintenanceWindow.from_json(json)
# print the JSON string representation of the object
print(SystemUpdateMaintenanceWindow.to_json())

# convert the object into a dict
system_update_maintenance_window_dict = system_update_maintenance_window_instance.to_dict()
# create an instance of SystemUpdateMaintenanceWindow from a dict
system_update_maintenance_window_from_dict = SystemUpdateMaintenanceWindow.from_dict(system_update_maintenance_window_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


