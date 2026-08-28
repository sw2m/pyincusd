# SystemStoragePoolKey

Currently the only supported type is \"zfs\".

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**encryption_key** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_pool_key import SystemStoragePoolKey

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStoragePoolKey from a JSON string
system_storage_pool_key_instance = SystemStoragePoolKey.from_json(json)
# print the JSON string representation of the object
print(SystemStoragePoolKey.to_json())

# convert the object into a dict
system_storage_pool_key_dict = system_storage_pool_key_instance.to_dict()
# create an instance of SystemStoragePoolKey from a dict
system_storage_pool_key_from_dict = SystemStoragePoolKey.from_dict(system_storage_pool_key_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


