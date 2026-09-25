# SystemStorageDrive


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**boot** | **bool** |  | [optional] 
**bus** | **str** |  | [optional] 
**capacity_in_bytes** | **int** |  | [optional] 
**encrypted** | **bool** |  | [optional] 
**encrypted_id** | **str** |  | [optional] 
**id** | **str** |  | [optional] 
**member_pool** | **str** |  | [optional] 
**model_family** | **str** |  | [optional] 
**model_name** | **str** |  | [optional] 
**multipath** | **bool** |  | [optional] 
**remote** | **bool** |  | [optional] 
**removable** | **bool** |  | [optional] 
**serial_number** | **str** |  | [optional] 
**smart** | [**SystemStorageDriveSMART**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemStorageDriveSMART.md) |  | [optional] 
**wwn** | **str** |  | [optional] 
**wwn_id** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_drive import SystemStorageDrive

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStorageDrive from a JSON string
system_storage_drive_instance = SystemStorageDrive.from_json(json)
# print the JSON string representation of the object
print(SystemStorageDrive.to_json())

# convert the object into a dict
system_storage_drive_dict = system_storage_drive_instance.to_dict()
# create an instance of SystemStorageDrive from a dict
system_storage_drive_from_dict = SystemStorageDrive.from_dict(system_storage_drive_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


