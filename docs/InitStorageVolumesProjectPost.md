# InitStorageVolumesProjectPost


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pool** | **str** | Storage pool in which the volume will reside | [optional] 
**project** | **str** | Project in which the volume will reside | [optional] 
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**content_type** | **str** | Volume content type (filesystem or block)  API extension: custom_block_volumes | [optional] 
**description** | **str** | Description of the storage volume  API extension: entity_description | [optional] 
**name** | **str** | Volume name | [optional] 
**restore** | **str** | Name of a snapshot to restore  API extension: storage_api_volume_snapshots | [optional] 
**source** | [**StorageVolumeSource**](https://github.com/anonhostpi/pyincusd/blob/v7.3.0/docs/StorageVolumeSource.md) |  | [optional] 
**type** | **str** | Volume type (container, custom, image or virtual-machine) | [optional] 

## Example

```python
from pyincusd.models.init_storage_volumes_project_post import InitStorageVolumesProjectPost

# TODO update the JSON string below
json = "{}"
# create an instance of InitStorageVolumesProjectPost from a JSON string
init_storage_volumes_project_post_instance = InitStorageVolumesProjectPost.from_json(json)
# print the JSON string representation of the object
print(InitStorageVolumesProjectPost.to_json())

# convert the object into a dict
init_storage_volumes_project_post_dict = init_storage_volumes_project_post_instance.to_dict()
# create an instance of InitStorageVolumesProjectPost from a dict
init_storage_volumes_project_post_from_dict = InitStorageVolumesProjectPost.from_dict(init_storage_volumes_project_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


