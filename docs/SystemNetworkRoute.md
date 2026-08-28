# SystemNetworkRoute


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**to** | **str** |  | [optional] 
**via** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_route import SystemNetworkRoute

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkRoute from a JSON string
system_network_route_instance = SystemNetworkRoute.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkRoute.to_json())

# convert the object into a dict
system_network_route_dict = system_network_route_instance.to_dict()
# create an instance of SystemNetworkRoute from a dict
system_network_route_from_dict = SystemNetworkRoute.from_dict(system_network_route_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


