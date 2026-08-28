# SystemStorageEncrypt


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**secure_wipe** | **bool** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_encrypt import SystemStorageEncrypt

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStorageEncrypt from a JSON string
system_storage_encrypt_instance = SystemStorageEncrypt.from_json(json)
# print the JSON string representation of the object
print(SystemStorageEncrypt.to_json())

# convert the object into a dict
system_storage_encrypt_dict = system_storage_encrypt_instance.to_dict()
# create an instance of SystemStorageEncrypt from a dict
system_storage_encrypt_from_dict = SystemStorageEncrypt.from_dict(system_storage_encrypt_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


