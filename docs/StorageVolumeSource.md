# StorageVolumeSource

StorageVolumeSource represents the creation source for a new storage volume

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**certificate** | **str** | Certificate (for migration)  API extension: storage_api_remote_volume_handling | [optional] 
**location** | **str** | What cluster member this record was found on  API extension: cluster_internal_custom_volume_copy | [optional] 
**mode** | **str** | Whether to use pull or push mode (for migration)  API extension: storage_api_remote_volume_handling | [optional] 
**name** | **str** | Source volume name (for copy) | [optional] 
**operation** | **str** | Remote operation URL (for migration)  API extension: storage_api_remote_volume_handling | [optional] 
**pool** | **str** | Source storage pool (for copy) | [optional] 
**project** | **str** | Source project name  API extension: storage_api_project | [optional] 
**refresh** | **bool** | Whether existing destination volume should be refreshed  API extension: custom_volume_refresh | [optional] 
**refresh_exclude_older** | **bool** | Whether to exclude source snapshots earlier than latest target snapshot  API extension: custom_volume_refresh_exclude_older_snapshots | [optional] 
**secrets** | **Dict[str, str]** | Map of migration websockets (for migration)  API extension: storage_api_remote_volume_handling | [optional] 
**type** | **str** | Source type (copy or migration) | [optional] 
**volume_only** | **bool** | Whether snapshots should be discarded (for migration)  API extension: storage_api_volume_snapshots | [optional] 

## Example

```python
from pyincusd.models.storage_volume_source import StorageVolumeSource

# TODO update the JSON string below
json = "{}"
# create an instance of StorageVolumeSource from a JSON string
storage_volume_source_instance = StorageVolumeSource.from_json(json)
# print the JSON string representation of the object
print(StorageVolumeSource.to_json())

# convert the object into a dict
storage_volume_source_dict = storage_volume_source_instance.to_dict()
# create an instance of StorageVolumeSource from a dict
storage_volume_source_from_dict = StorageVolumeSource.from_dict(storage_volume_source_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


