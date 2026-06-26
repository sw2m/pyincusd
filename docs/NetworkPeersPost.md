# NetworkPeersPost

NetworkPeersPost represents the fields of a new network peering

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the peer | [optional] 
**name** | **str** | Name of the peer | [optional] 
**target_integration** | **str** | Name of the target integration  API extension: network_integrations. | [optional] 
**target_network** | **str** | Name of the target network | [optional] 
**target_project** | **str** | Name of the target project | [optional] 
**type** | **str** | Type of peer  API extension: network_integrations. | [optional] 

## Example

```python
from pyincusd.models.network_peers_post import NetworkPeersPost

# TODO update the JSON string below
json = "{}"
# create an instance of NetworkPeersPost from a JSON string
network_peers_post_instance = NetworkPeersPost.from_json(json)
# print the JSON string representation of the object
print(NetworkPeersPost.to_json())

# convert the object into a dict
network_peers_post_dict = network_peers_post_instance.to_dict()
# create an instance of NetworkPeersPost from a dict
network_peers_post_from_dict = NetworkPeersPost.from_dict(network_peers_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


