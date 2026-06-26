# StorageVolumePut

StorageVolumePut represents the modifiable fields of a storage volume

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the storage volume  API extension: entity_description | [optional] 
**restore** | **str** | Name of a snapshot to restore  API extension: storage_api_volume_snapshots | [optional] 

## Example

```python
from pyincusd.models.storage_volume_put import StorageVolumePut

# TODO update the JSON string below
json = "{}"
# create an instance of StorageVolumePut from a JSON string
storage_volume_put_instance = StorageVolumePut.from_json(json)
# print the JSON string representation of the object
print(StorageVolumePut.to_json())

# convert the object into a dict
storage_volume_put_dict = storage_volume_put_instance.to_dict()
# create an instance of StorageVolumePut from a dict
storage_volume_put_from_dict = StorageVolumePut.from_dict(storage_volume_put_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


