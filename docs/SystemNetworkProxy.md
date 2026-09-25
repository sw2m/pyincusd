# SystemNetworkProxy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rules** | [**List[SystemNetworkProxyRule]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkProxyRule.md) |  | [optional] 
**servers** | [**Dict[str, SystemNetworkProxyServer]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkProxyServer.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_network_proxy import SystemNetworkProxy

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkProxy from a JSON string
system_network_proxy_instance = SystemNetworkProxy.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkProxy.to_json())

# convert the object into a dict
system_network_proxy_dict = system_network_proxy_instance.to_dict()
# create an instance of SystemNetworkProxy from a dict
system_network_proxy_from_dict = SystemNetworkProxy.from_dict(system_network_proxy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


