# SystemNetworkConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bonds** | [**List[SystemNetworkBond]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkBond.md) |  | [optional] 
**confirmation_timeout** | **str** | If defined, automatically roll back the new network changes after the specified timeout has elapsed unless those changes are confirmed before then. | [optional] 
**dns** | [**SystemNetworkDNS**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkDNS.md) |  | [optional] 
**interfaces** | [**List[SystemNetworkInterface]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkInterface.md) |  | [optional] 
**proxy** | [**SystemNetworkProxy**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkProxy.md) |  | [optional] 
**time** | [**SystemNetworkTime**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkTime.md) |  | [optional] 
**vlans** | [**List[SystemNetworkVLAN]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkVLAN.md) |  | [optional] 
**wireguard** | [**List[SystemNetworkWireguard]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemNetworkWireguard.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_network_config import SystemNetworkConfig

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkConfig from a JSON string
system_network_config_instance = SystemNetworkConfig.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkConfig.to_json())

# convert the object into a dict
system_network_config_dict = system_network_config_instance.to_dict()
# create an instance of SystemNetworkConfig from a dict
system_network_config_from_dict = SystemNetworkConfig.from_dict(system_network_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


