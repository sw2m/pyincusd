# ProjectPut

ProjectPut represents the modifiable fields of a project

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the project | [optional] 

## Example

```python
from pyincusd.models.project_put import ProjectPut

# TODO update the JSON string below
json = "{}"
# create an instance of ProjectPut from a JSON string
project_put_instance = ProjectPut.from_json(json)
# print the JSON string representation of the object
print(ProjectPut.to_json())

# convert the object into a dict
project_put_dict = project_put_instance.to_dict()
# create an instance of ProjectPut from a dict
project_put_from_dict = ProjectPut.from_dict(project_put_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


