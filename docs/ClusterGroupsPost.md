# ClusterGroupsPost


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | The description of the cluster group | [optional] 
**members** | **List[str]** | List of members in this group | [optional] 
**name** | **str** | The new name of the cluster group | [optional] 

## Example

```python
from pyincusd.models.cluster_groups_post import ClusterGroupsPost

# TODO update the JSON string below
json = "{}"
# create an instance of ClusterGroupsPost from a JSON string
cluster_groups_post_instance = ClusterGroupsPost.from_json(json)
# print the JSON string representation of the object
print(ClusterGroupsPost.to_json())

# convert the object into a dict
cluster_groups_post_dict = cluster_groups_post_instance.to_dict()
# create an instance of ClusterGroupsPost from a dict
cluster_groups_post_from_dict = ClusterGroupsPost.from_dict(cluster_groups_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


