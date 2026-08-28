# SystemNetworkEthernet


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**disable_energy_efficient** | **bool** |  | [optional] 
**disable_gro** | **bool** |  | [optional] 
**disable_gso** | **bool** |  | [optional] 
**disable_ipv4_tso** | **bool** |  | [optional] 
**disable_ipv6_tso** | **bool** |  | [optional] 
**rx_buffer_size** | **str** |  | [optional] 
**rx_jumbo_buffer_size** | **str** |  | [optional] 
**rx_mini_buffer_size** | **str** |  | [optional] 
**tx_buffer_size** | **str** |  | [optional] 
**wakeonlan** | **bool** |  | [optional] 
**wakeonlan_modes** | **List[str]** |  | [optional] 
**wakeonlan_password** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_ethernet import SystemNetworkEthernet

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkEthernet from a JSON string
system_network_ethernet_instance = SystemNetworkEthernet.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkEthernet.to_json())

# convert the object into a dict
system_network_ethernet_dict = system_network_ethernet_instance.to_dict()
# create an instance of SystemNetworkEthernet from a dict
system_network_ethernet_from_dict = SystemNetworkEthernet.from_dict(system_network_ethernet_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


