# StorageBucket

StorageBucket represents the fields of a storage pool bucket

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the storage bucket  API extension: storage_buckets | [optional] 
**location** | **str** | What cluster member this record was found on  API extension: storage_buckets | [optional] 
**name** | **str** | Bucket name  API extension: storage_buckets | [optional] 
**project** | **str** | Project name  API extension: storage_buckets_all_projects | [optional] 
**s3_url** | **str** | Bucket S3 URL  API extension: storage_buckets | [optional] 

## Example

```python
from pyincusd.models.storage_bucket import StorageBucket

# TODO update the JSON string below
json = "{}"
# create an instance of StorageBucket from a JSON string
storage_bucket_instance = StorageBucket.from_json(json)
# print the JSON string representation of the object
print(StorageBucket.to_json())

# convert the object into a dict
storage_bucket_dict = storage_bucket_instance.to_dict()
# create an instance of StorageBucket from a dict
storage_bucket_from_dict = StorageBucket.from_dict(storage_bucket_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


