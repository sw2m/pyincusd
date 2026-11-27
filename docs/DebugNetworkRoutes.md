# DebugNetworkRoutes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ipv4_routes** | **List[Dict[str, object]]** |  | [optional] 
**ipv4_rules** | **List[Dict[str, object]]** |  | [optional] 
**ipv6_routes** | **List[Dict[str, object]]** |  | [optional] 
**ipv6_rules** | **List[Dict[str, object]]** |  | [optional] 

## Example

```python
from pyincusd.models.debug_network_routes import DebugNetworkRoutes

# TODO update the JSON string below
json = "{}"
# create an instance of DebugNetworkRoutes from a JSON string
debug_network_routes_instance = DebugNetworkRoutes.from_json(json)
# print the JSON string representation of the object
print(DebugNetworkRoutes.to_json())

# convert the object into a dict
debug_network_routes_dict = debug_network_routes_instance.to_dict()
# create an instance of DebugNetworkRoutes from a dict
debug_network_routes_from_dict = DebugNetworkRoutes.from_dict(debug_network_routes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


