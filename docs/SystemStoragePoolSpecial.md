# SystemStoragePoolSpecial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | **List[str]** | One or more physical devices to create the pool&#39;s special vdev. | [optional] 
**special_small_blocks_size_in_kb** | **int** | If non-zero, will be used when setting the pool&#39;s special_small_blocks property. | [optional] 
**type** | **str** | Supported special device types: zfs-raid0, zfs-raid1, zfs-raid10, zfs-raidz1, zfs-raidz2, zfs-raidz3. | [optional] 

## Example

```python
from pyincusd.models.system_storage_pool_special import SystemStoragePoolSpecial

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStoragePoolSpecial from a JSON string
system_storage_pool_special_instance = SystemStoragePoolSpecial.from_json(json)
# print the JSON string representation of the object
print(SystemStoragePoolSpecial.to_json())

# convert the object into a dict
system_storage_pool_special_dict = system_storage_pool_special_instance.to_dict()
# create an instance of SystemStoragePoolSpecial from a dict
system_storage_pool_special_from_dict = SystemStoragePoolSpecial.from_dict(system_storage_pool_special_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


