# SystemStoragePoolTrimStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**errors** | **int** |  | [optional] 
**last_action_time** | **datetime** |  | [optional] 
**progress** | **str** |  | [optional] 
**state** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_pool_trim_status import SystemStoragePoolTrimStatus

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStoragePoolTrimStatus from a JSON string
system_storage_pool_trim_status_instance = SystemStoragePoolTrimStatus.from_json(json)
# print the JSON string representation of the object
print(SystemStoragePoolTrimStatus.to_json())

# convert the object into a dict
system_storage_pool_trim_status_dict = system_storage_pool_trim_status_instance.to_dict()
# create an instance of SystemStoragePoolTrimStatus from a dict
system_storage_pool_trim_status_from_dict = SystemStoragePoolTrimStatus.from_dict(system_storage_pool_trim_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


