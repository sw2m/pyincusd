# SystemStorageConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pools** | [**List[SystemStoragePool]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemStoragePool.md) |  | [optional] 
**scrub_schedule** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_config import SystemStorageConfig

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStorageConfig from a JSON string
system_storage_config_instance = SystemStorageConfig.from_json(json)
# print the JSON string representation of the object
print(SystemStorageConfig.to_json())

# convert the object into a dict
system_storage_config_dict = system_storage_config_instance.to_dict()
# create an instance of SystemStorageConfig from a dict
system_storage_config_from_dict = SystemStorageConfig.from_dict(system_storage_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


