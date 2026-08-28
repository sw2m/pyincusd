# SystemStoragePoolVolume


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**quota_in_bytes** | **int** |  | [optional] 
**usage_in_bytes** | **int** |  | [optional] 
**use** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_pool_volume import SystemStoragePoolVolume

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStoragePoolVolume from a JSON string
system_storage_pool_volume_instance = SystemStoragePoolVolume.from_json(json)
# print the JSON string representation of the object
print(SystemStoragePoolVolume.to_json())

# convert the object into a dict
system_storage_pool_volume_dict = system_storage_pool_volume_instance.to_dict()
# create an instance of SystemStoragePoolVolume from a dict
system_storage_pool_volume_from_dict = SystemStoragePoolVolume.from_dict(system_storage_pool_volume_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


