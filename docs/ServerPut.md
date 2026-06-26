# ServerPut

ServerPut represents the modifiable fields of a server configuration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 

## Example

```python
from pyincusd.models.server_put import ServerPut

# TODO update the JSON string below
json = "{}"
# create an instance of ServerPut from a JSON string
server_put_instance = ServerPut.from_json(json)
# print the JSON string representation of the object
print(ServerPut.to_json())

# convert the object into a dict
server_put_dict = server_put_instance.to_dict()
# create an instance of ServerPut from a dict
server_put_from_dict = ServerPut.from_dict(server_put_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


