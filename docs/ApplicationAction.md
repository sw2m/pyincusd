# ApplicationAction


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**config** | **Dict[str, str]** |  | [optional] 

## Example

```python
from pyincusd.models.application_action import ApplicationAction

# TODO update the JSON string below
json = "{}"
# create an instance of ApplicationAction from a JSON string
application_action_instance = ApplicationAction.from_json(json)
# print the JSON string representation of the object
print(ApplicationAction.to_json())

# convert the object into a dict
application_action_dict = application_action_instance.to_dict()
# create an instance of ApplicationAction from a dict
application_action_from_dict = ApplicationAction.from_dict(application_action_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


