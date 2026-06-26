# InstanceSnapshot


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**architecture** | **str** | Architecture name | [optional] 
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**created_at** | **datetime** | Instance creation timestamp | [optional] 
**description** | **str** | Instance description | [optional] 
**devices** | **object** | DevicesMap type is used to hold incus devices configurations. In contrast to plain map[string]map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**ephemeral** | **bool** | Whether the instance is ephemeral (deleted on shutdown) | [optional] 
**expanded_config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**expanded_devices** | **object** | DevicesMap type is used to hold incus devices configurations. In contrast to plain map[string]map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**expires_at** | **datetime** | When the snapshot expires (gets auto-deleted) | [optional] 
**last_used_at** | **datetime** | Last start timestamp | [optional] 
**name** | **str** | Snapshot name | [optional] 
**profiles** | **List[str]** | List of profiles applied to the instance | [optional] 
**size** | **int** | Size of the snapshot in bytes  API extension: snapshot_disk_usage | [optional] 
**stateful** | **bool** | Whether the instance currently has saved state on disk | [optional] 

## Example

```python
from pyincusd.models.instance_snapshot import InstanceSnapshot

# TODO update the JSON string below
json = "{}"
# create an instance of InstanceSnapshot from a JSON string
instance_snapshot_instance = InstanceSnapshot.from_json(json)
# print the JSON string representation of the object
print(InstanceSnapshot.to_json())

# convert the object into a dict
instance_snapshot_dict = instance_snapshot_instance.to_dict()
# create an instance of InstanceSnapshot from a dict
instance_snapshot_from_dict = InstanceSnapshot.from_dict(instance_snapshot_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


