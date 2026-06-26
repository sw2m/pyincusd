# StorageBucketsPost

StorageBucketsPost represents the fields of a new storage pool bucket

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the storage bucket  API extension: storage_buckets | [optional] 
**name** | **str** | Bucket name  API extension: storage_buckets | [optional] 

## Example

```python
from pyincusd.models.storage_buckets_post import StorageBucketsPost

# TODO update the JSON string below
json = "{}"
# create an instance of StorageBucketsPost from a JSON string
storage_buckets_post_instance = StorageBucketsPost.from_json(json)
# print the JSON string representation of the object
print(StorageBucketsPost.to_json())

# convert the object into a dict
storage_buckets_post_dict = storage_buckets_post_instance.to_dict()
# create an instance of StorageBucketsPost from a dict
storage_buckets_post_from_dict = StorageBucketsPost.from_dict(storage_buckets_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


