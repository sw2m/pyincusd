# InstanceFull


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**architecture** | **str** | Architecture name | [optional] 
**backups** | [**List[InstanceBackup]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/InstanceBackup.md) | List of backups. | [optional] 
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**created_at** | **datetime** | Instance creation timestamp | [optional] 
**description** | **str** | Instance description | [optional] 
**devices** | **object** | DevicesMap type is used to hold incus devices configurations. In contrast to plain map[string]map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**disk_only** | **bool** | Whether only the instances disk should be restored | [optional] 
**ephemeral** | **bool** | Whether the instance is ephemeral (deleted on shutdown) | [optional] 
**expanded_config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**expanded_devices** | **object** | DevicesMap type is used to hold incus devices configurations. In contrast to plain map[string]map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**last_used_at** | **datetime** | Last start timestamp | [optional] 
**location** | **str** | What cluster member this instance is located on | [optional] 
**name** | **str** | Instance name | [optional] 
**profiles** | **List[str]** | List of profiles applied to the instance | [optional] 
**project** | **str** | Instance project name  API extension: instance_all_projects | [optional] 
**restore** | **str** | If set, instance will be restored to the provided snapshot name | [optional] 
**snapshots** | [**List[InstanceSnapshot]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/InstanceSnapshot.md) | List of snapshots. | [optional] 
**state** | [**InstanceState**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/InstanceState.md) |  | [optional] 
**stateful** | **bool** | Whether the instance currently has saved state on disk | [optional] 
**status** | **str** | Instance status (see instance_state) | [optional] 
**status_code** | **int** |  | [optional] 
**type** | **str** | The type of instance (container or virtual-machine) | [optional] 

## Example

```python
from pyincusd.models.instance_full import InstanceFull

# TODO update the JSON string below
json = "{}"
# create an instance of InstanceFull from a JSON string
instance_full_instance = InstanceFull.from_json(json)
# print the JSON string representation of the object
print(InstanceFull.to_json())

# convert the object into a dict
instance_full_dict = instance_full_instance.to_dict()
# create an instance of InstanceFull from a dict
instance_full_from_dict = InstanceFull.from_dict(instance_full_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


