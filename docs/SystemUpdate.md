# SystemUpdate


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | [**SystemUpdateConfig**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemUpdateConfig.md) |  | [optional] 
**state** | [**SystemUpdateState**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemUpdateState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_update import SystemUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of SystemUpdate from a JSON string
system_update_instance = SystemUpdate.from_json(json)
# print the JSON string representation of the object
print(SystemUpdate.to_json())

# convert the object into a dict
system_update_dict = system_update_instance.to_dict()
# create an instance of SystemUpdate from a dict
system_update_from_dict = SystemUpdate.from_dict(system_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


