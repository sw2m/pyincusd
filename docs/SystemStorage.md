# SystemStorage


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | [**SystemStorageConfig**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemStorageConfig.md) |  | [optional] 
**state** | [**SystemStorageState**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemStorageState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_storage import SystemStorage

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStorage from a JSON string
system_storage_instance = SystemStorage.from_json(json)
# print the JSON string representation of the object
print(SystemStorage.to_json())

# convert the object into a dict
system_storage_dict = system_storage_instance.to_dict()
# create an instance of SystemStorage from a dict
system_storage_from_dict = SystemStorage.from_dict(system_storage_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


