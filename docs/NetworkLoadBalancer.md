# NetworkLoadBalancer

NetworkLoadBalancer used for displaying a network load balancer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**backends** | [**List[NetworkLoadBalancerBackend]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/NetworkLoadBalancerBackend.md) | Backends (optional) | [optional] 
**config** | **object** | ConfigMap type is used to hold incus config. In contrast to plain map[string]string it provides unmarshal methods for JSON and YAML, which gracefully handle numbers and bools. | [optional] 
**description** | **str** | Description of the load balancer listen IP | [optional] 
**listen_address** | **str** | The listen address of the load balancer | [optional] 
**location** | **str** | What cluster member this record was found on | [optional] 
**ports** | [**List[NetworkLoadBalancerPort]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/NetworkLoadBalancerPort.md) | Port forwards (optional) | [optional] 

## Example

```python
from pyincusd.models.network_load_balancer import NetworkLoadBalancer

# TODO update the JSON string below
json = "{}"
# create an instance of NetworkLoadBalancer from a JSON string
network_load_balancer_instance = NetworkLoadBalancer.from_json(json)
# print the JSON string representation of the object
print(NetworkLoadBalancer.to_json())

# convert the object into a dict
network_load_balancer_dict = network_load_balancer_instance.to_dict()
# create an instance of NetworkLoadBalancer from a dict
network_load_balancer_from_dict = NetworkLoadBalancer.from_dict(network_load_balancer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


