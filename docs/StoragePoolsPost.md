# StoragePoolsPost

StoragePoolsPost represents the fields of a new storage pool

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the storage pool  API extension: entity_description | [optional] 
**driver** | **str** | Storage pool driver (btrfs, ceph, cephfs, cephobject, dir, lvm, lvmcluster or zfs) | [optional] 
**name** | **str** | Storage pool name | [optional] 

## Example

```python
from pyincusd.models.storage_pools_post import StoragePoolsPost

# TODO update the JSON string below
json = "{}"
# create an instance of StoragePoolsPost from a JSON string
storage_pools_post_instance = StoragePoolsPost.from_json(json)
# print the JSON string representation of the object
print(StoragePoolsPost.to_json())

# convert the object into a dict
storage_pools_post_dict = storage_pools_post_instance.to_dict()
# create an instance of StoragePoolsPost from a dict
storage_pools_post_from_dict = StoragePoolsPost.from_dict(storage_pools_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


