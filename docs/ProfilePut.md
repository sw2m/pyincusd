# ProfilePut

ProfilePut represents the modifiable fields of a profile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the profile | [optional] 
**devices** | **object** | DevicesMap type is used to hold incus devices configurations. In contrast to plain map[string]map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 

## Example

```python
from pyincusd.models.profile_put import ProfilePut

# TODO update the JSON string below
json = "{}"
# create an instance of ProfilePut from a JSON string
profile_put_instance = ProfilePut.from_json(json)
# print the JSON string representation of the object
print(ProfilePut.to_json())

# convert the object into a dict
profile_put_dict = profile_put_instance.to_dict()
# create an instance of ProfilePut from a dict
profile_put_from_dict = ProfilePut.from_dict(profile_put_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


