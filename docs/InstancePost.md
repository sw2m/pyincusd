# InstancePost


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**devices** | **object** | DevicesMap type is used to hold incus devices configurations. In contrast to plain map[string]map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**profiles** | **List[str]** | List of profiles applied to the instance.  API extension: instance_move_config | [optional] 
**allow_inconsistent** | **bool** | AllowInconsistent allow inconsistent copies when migrating.  API extension: instance_allow_inconsistent_copy | [optional] 
**instance_only** | **bool** | Whether snapshots should be discarded (migration only) | [optional] 
**live** | **bool** | Whether to perform a live migration (migration only) | [optional] 
**migration** | **bool** | Whether the instance is being migrated to another server | [optional] 
**name** | **str** | New name for the instance | [optional] 
**pool** | **str** | Target pool for local cross-pool move  API extension: instance_pool_move | [optional] 
**project** | **str** | Target project for local cross-project move  API extension: instance_project_move | [optional] 
**refresh** | **bool** | Whether to transfer a running instance incrementally  API extension: instance_refresh_migration | [optional] 
**target** | [**InstancePostTarget**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/InstancePostTarget.md) |  | [optional] 

## Example

```python
from pyincusd.models.instance_post import InstancePost

# TODO update the JSON string below
json = "{}"
# create an instance of InstancePost from a JSON string
instance_post_instance = InstancePost.from_json(json)
# print the JSON string representation of the object
print(InstancePost.to_json())

# convert the object into a dict
instance_post_dict = instance_post_instance.to_dict()
# create an instance of InstancePost from a dict
instance_post_from_dict = InstancePost.from_dict(instance_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


