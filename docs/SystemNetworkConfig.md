# SystemNetworkConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bonds** | [**List[SystemNetworkBond]**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemNetworkBond.md) |  | [optional] 
**confirmation_timeout** | **str** | If defined, automatically roll back the new network changes after the specified timeout has elapsed unless those changes are confirmed before then. | [optional] 
**default_confirmation_timeout** | **str** | If defined and no confirmation timeout provided, automatically roll back the new network changes after the specified timeout has elapsed unless those changes are confirmed before then. | [optional] 
**dns** | [**SystemNetworkDNS**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemNetworkDNS.md) |  | [optional] 
**ignore_service_checks** | **bool** | If true, when bringing up the network don&#39;t wait for DNS and NTP to be configured and available before continuing. Most systems shouldn&#39;t need to set this, and when enabled initial update checks may fail due to being unable to resolve hostnames. | [optional] 
**interfaces** | [**List[SystemNetworkInterface]**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemNetworkInterface.md) |  | [optional] 
**proxy** | [**SystemNetworkProxy**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemNetworkProxy.md) |  | [optional] 
**time** | [**SystemNetworkTime**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemNetworkTime.md) |  | [optional] 
**vlans** | [**List[SystemNetworkVLAN]**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemNetworkVLAN.md) |  | [optional] 
**wireguard** | [**List[SystemNetworkWireguard]**](https://github.com/anonhostpi/pyincusd/blob/v7.7.0/docs/SystemNetworkWireguard.md) |  | [optional] 

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


