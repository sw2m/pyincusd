# SystemStoragePoolScrubStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**end_time** | **datetime** |  | [optional] 
**errors** | **int** |  | [optional] 
**progress** | **str** |  | [optional] 
**start_time** | **datetime** |  | [optional] 
**state** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_pool_scrub_status import SystemStoragePoolScrubStatus

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStoragePoolScrubStatus from a JSON string
system_storage_pool_scrub_status_instance = SystemStoragePoolScrubStatus.from_json(json)
# print the JSON string representation of the object
print(SystemStoragePoolScrubStatus.to_json())

# convert the object into a dict
system_storage_pool_scrub_status_dict = system_storage_pool_scrub_status_instance.to_dict()
# create an instance of SystemStoragePoolScrubStatus from a dict
system_storage_pool_scrub_status_from_dict = SystemStoragePoolScrubStatus.from_dict(system_storage_pool_scrub_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


