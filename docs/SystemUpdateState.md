# SystemUpdateState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**last_check** | **datetime** |  | [optional] 
**needs_reboot** | **bool** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_update_state import SystemUpdateState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemUpdateState from a JSON string
system_update_state_instance = SystemUpdateState.from_json(json)
# print the JSON string representation of the object
print(SystemUpdateState.to_json())

# convert the object into a dict
system_update_state_dict = system_update_state_instance.to_dict()
# create an instance of SystemUpdateState from a dict
system_update_state_from_dict = SystemUpdateState.from_dict(system_update_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


