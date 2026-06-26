# NetworkForwardPut

NetworkForwardPut represents the modifiable fields of a network address forward

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the forward listen IP | [optional] 
**ports** | [**List[NetworkForwardPort]**](https://github.com/anonhostpi/pyincusd/blob/v7.2.0/docs/NetworkForwardPort.md) | Port forwards (optional) | [optional] 

## Example

```python
from pyincusd.models.network_forward_put import NetworkForwardPut

# TODO update the JSON string below
json = "{}"
# create an instance of NetworkForwardPut from a JSON string
network_forward_put_instance = NetworkForwardPut.from_json(json)
# print the JSON string representation of the object
print(NetworkForwardPut.to_json())

# convert the object into a dict
network_forward_put_dict = network_forward_put_instance.to_dict()
# create an instance of NetworkForwardPut from a dict
network_forward_put_from_dict = NetworkForwardPut.from_dict(network_forward_put_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


