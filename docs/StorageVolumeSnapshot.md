# StorageVolumeSnapshot

StorageVolumeSnapshot represents a storage volume snapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**content_type** | **str** | The content type (filesystem or block)  API extension: custom_block_volumes | [optional] 
**created_at** | **datetime** | Volume snapshot creation timestamp API extension: storage_volumes_created_at | [optional] 
**description** | **str** | Description of the storage volume | [optional] 
**expires_at** | **datetime** | When the snapshot expires (gets auto-deleted)  API extension: custom_volume_snapshot_expiry | [optional] 
**name** | **str** | Snapshot name | [optional] 

## Example

```python
from pyincusd.models.storage_volume_snapshot import StorageVolumeSnapshot

# TODO update the JSON string below
json = "{}"
# create an instance of StorageVolumeSnapshot from a JSON string
storage_volume_snapshot_instance = StorageVolumeSnapshot.from_json(json)
# print the JSON string representation of the object
print(StorageVolumeSnapshot.to_json())

# convert the object into a dict
storage_volume_snapshot_dict = storage_volume_snapshot_instance.to_dict()
# create an instance of StorageVolumeSnapshot from a dict
storage_volume_snapshot_from_dict = StorageVolumeSnapshot.from_dict(storage_volume_snapshot_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


