# StorageVolumeFull


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**backups** | [**List[StorageVolumeBackup]**](https://github.com/anonhostpi/pyincusd/blob/v7.2.0/docs/StorageVolumeBackup.md) | List of backups. | [optional] 
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**content_type** | **str** | Volume content type (filesystem or block)  API extension: custom_block_volumes | [optional] 
**created_at** | **datetime** | Volume creation timestamp API extension: storage_volumes_created_at | [optional] 
**description** | **str** | Description of the storage volume  API extension: entity_description | [optional] 
**location** | **str** | What cluster member this record was found on  API extension: clustering | [optional] 
**name** | **str** | Volume name | [optional] 
**project** | **str** | Project containing the volume.  API extension: storage_volumes_all_projects | [optional] 
**restore** | **str** | Name of a snapshot to restore  API extension: storage_api_volume_snapshots | [optional] 
**snapshots** | [**List[StorageVolumeSnapshot]**](https://github.com/anonhostpi/pyincusd/blob/v7.2.0/docs/StorageVolumeSnapshot.md) | List of snapshots. | [optional] 
**state** | [**StorageVolumeState**](https://github.com/anonhostpi/pyincusd/blob/v7.2.0/docs/StorageVolumeState.md) |  | [optional] 
**type** | **str** | Volume type | [optional] 
**used_by** | **List[str]** | List of URLs of objects using this storage volume | [optional] 

## Example

```python
from pyincusd.models.storage_volume_full import StorageVolumeFull

# TODO update the JSON string below
json = "{}"
# create an instance of StorageVolumeFull from a JSON string
storage_volume_full_instance = StorageVolumeFull.from_json(json)
# print the JSON string representation of the object
print(StorageVolumeFull.to_json())

# convert the object into a dict
storage_volume_full_dict = storage_volume_full_instance.to_dict()
# create an instance of StorageVolumeFull from a dict
storage_volume_full_from_dict = StorageVolumeFull.from_dict(storage_volume_full_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


