# NetworkPut

NetworkPut represents the modifiable fields of a network

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the profile  API extension: entity_description | [optional] 

## Example

```python
from pyincusd.models.network_put import NetworkPut

# TODO update the JSON string below
json = "{}"
# create an instance of NetworkPut from a JSON string
network_put_instance = NetworkPut.from_json(json)
# print the JSON string representation of the object
print(NetworkPut.to_json())

# convert the object into a dict
network_put_dict = network_put_instance.to_dict()
# create an instance of NetworkPut from a dict
network_put_from_dict = NetworkPut.from_dict(network_put_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


