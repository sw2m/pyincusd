# ServiceAction


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**config** | **Dict[str, str]** |  | [optional] 

## Example

```python
from pyincusd.models.service_action import ServiceAction

# TODO update the JSON string below
json = "{}"
# create an instance of ServiceAction from a JSON string
service_action_instance = ServiceAction.from_json(json)
# print the JSON string representation of the object
print(ServiceAction.to_json())

# convert the object into a dict
service_action_dict = service_action_instance.to_dict()
# create an instance of ServiceAction from a dict
service_action_from_dict = ServiceAction.from_dict(service_action_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


