# SystemStorageState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**drives** | [**List[SystemStorageDrive]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemStorageDrive.md) |  | [optional] 
**root_partition** | [**SystemStorageRootPartition**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemStorageRootPartition.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_state import SystemStorageState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStorageState from a JSON string
system_storage_state_instance = SystemStorageState.from_json(json)
# print the JSON string representation of the object
print(SystemStorageState.to_json())

# convert the object into a dict
system_storage_state_dict = system_storage_state_instance.to_dict()
# create an instance of SystemStorageState from a dict
system_storage_state_from_dict = SystemStorageState.from_dict(system_storage_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


