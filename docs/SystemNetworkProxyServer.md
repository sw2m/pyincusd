# SystemNetworkProxyServer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | **str** |  | [optional] 
**host** | **str** |  | [optional] 
**password** | **str** |  | [optional] 
**realm** | **str** |  | [optional] 
**use_tls** | **bool** |  | [optional] 
**username** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_proxy_server import SystemNetworkProxyServer

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkProxyServer from a JSON string
system_network_proxy_server_instance = SystemNetworkProxyServer.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkProxyServer.to_json())

# convert the object into a dict
system_network_proxy_server_dict = system_network_proxy_server_instance.to_dict()
# create an instance of SystemNetworkProxyServer from a dict
system_network_proxy_server_from_dict = SystemNetworkProxyServer.from_dict(system_network_proxy_server_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


