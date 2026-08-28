# SystemStorageDriveSMART


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**available_spare** | **int** |  | [optional] 
**data_units_read** | **int** |  | [optional] 
**data_units_written** | **int** |  | [optional] 
**enabled** | **bool** |  | [optional] 
**error** | **str** |  | [optional] 
**passed** | **bool** |  | [optional] 
**percentage_used** | **int** |  | [optional] 
**power_on_hours** | **int** |  | [optional] 
**raw_read_error_rate** | **int** |  | [optional] 
**reallocated_sectors** | **int** |  | [optional] 
**seek_error_rate** | **int** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_drive_smart import SystemStorageDriveSMART

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStorageDriveSMART from a JSON string
system_storage_drive_smart_instance = SystemStorageDriveSMART.from_json(json)
# print the JSON string representation of the object
print(SystemStorageDriveSMART.to_json())

# convert the object into a dict
system_storage_drive_smart_dict = system_storage_drive_smart_instance.to_dict()
# create an instance of SystemStorageDriveSMART from a dict
system_storage_drive_smart_from_dict = SystemStorageDriveSMART.from_dict(system_storage_drive_smart_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


