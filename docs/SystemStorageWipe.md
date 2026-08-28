# SystemStorageWipe


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**secure_wipe** | **bool** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_wipe import SystemStorageWipe

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStorageWipe from a JSON string
system_storage_wipe_instance = SystemStorageWipe.from_json(json)
# print the JSON string representation of the object
print(SystemStorageWipe.to_json())

# convert the object into a dict
system_storage_wipe_dict = system_storage_wipe_instance.to_dict()
# create an instance of SystemStorageWipe from a dict
system_storage_wipe_from_dict = SystemStorageWipe.from_dict(system_storage_wipe_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


