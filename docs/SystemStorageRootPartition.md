# SystemStorageRootPartition


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**available_in_bytes** | **int** |  | [optional] 
**size_in_bytes** | **int** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_root_partition import SystemStorageRootPartition

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStorageRootPartition from a JSON string
system_storage_root_partition_instance = SystemStorageRootPartition.from_json(json)
# print the JSON string representation of the object
print(SystemStorageRootPartition.to_json())

# convert the object into a dict
system_storage_root_partition_dict = system_storage_root_partition_instance.to_dict()
# create an instance of SystemStorageRootPartition from a dict
system_storage_root_partition_from_dict = SystemStorageRootPartition.from_dict(system_storage_root_partition_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


