# SystemNetwork


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | [**SystemNetworkConfig**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkConfig.md) |  | [optional] 
**state** | [**SystemNetworkState**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_network import SystemNetwork

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetwork from a JSON string
system_network_instance = SystemNetwork.from_json(json)
# print the JSON string representation of the object
print(SystemNetwork.to_json())

# convert the object into a dict
system_network_dict = system_network_instance.to_dict()
# create an instance of SystemNetwork from a dict
system_network_from_dict = SystemNetwork.from_dict(system_network_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


