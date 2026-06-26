# StorageVolumePost

StorageVolumePost represents the fields required to rename a storage pool volume

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**migration** | **bool** | Initiate volume migration  API extension: storage_api_remote_volume_handling | [optional] 
**name** | **str** | New volume name | [optional] 
**pool** | **str** | New storage pool  API extension: storage_api_local_volume_handling | [optional] 
**project** | **str** | New project name  API extension: storage_volume_project_move | [optional] 
**source** | [**StorageVolumeSource**](https://github.com/anonhostpi/pyincusd/blob/v7.2.0/docs/StorageVolumeSource.md) |  | [optional] 
**target** | [**StorageVolumePostTarget**](https://github.com/anonhostpi/pyincusd/blob/v7.2.0/docs/StorageVolumePostTarget.md) |  | [optional] 
**volume_only** | **bool** | Whether snapshots should be discarded (migration only)  API extension: storage_api_remote_volume_snapshots | [optional] 

## Example

```python
from pyincusd.models.storage_volume_post import StorageVolumePost

# TODO update the JSON string below
json = "{}"
# create an instance of StorageVolumePost from a JSON string
storage_volume_post_instance = StorageVolumePost.from_json(json)
# print the JSON string representation of the object
print(StorageVolumePost.to_json())

# convert the object into a dict
storage_volume_post_dict = storage_volume_post_instance.to_dict()
# create an instance of StorageVolumePost from a dict
storage_volume_post_from_dict = StorageVolumePost.from_dict(storage_volume_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


