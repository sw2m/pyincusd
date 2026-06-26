# StoragePool


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the storage pool  API extension: entity_description | [optional] 
**driver** | **str** | Storage pool driver (btrfs, ceph, cephfs, cephobject, dir, lvm, lvmcluster or zfs) | [optional] 
**locations** | **List[str]** | Cluster members on which the storage pool has been defined  API extension: clustering | [optional] [readonly] 
**name** | **str** | Storage pool name | [optional] 
**status** | **str** | Pool status (Pending, Created, Errored or Unknown)  API extension: clustering | [optional] [readonly] 
**used_by** | **List[str]** | List of URLs of objects using this storage pool | [optional] 

## Example

```python
from pyincusd.models.storage_pool import StoragePool

# TODO update the JSON string below
json = "{}"
# create an instance of StoragePool from a JSON string
storage_pool_instance = StoragePool.from_json(json)
# print the JSON string representation of the object
print(StoragePool.to_json())

# convert the object into a dict
storage_pool_dict = storage_pool_instance.to_dict()
# create an instance of StoragePool from a dict
storage_pool_from_dict = StoragePool.from_dict(storage_pool_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


