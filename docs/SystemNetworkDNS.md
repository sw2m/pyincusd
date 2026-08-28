# SystemNetworkDNS


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dns_over_tls** | **bool** |  | [optional] 
**domain** | **str** |  | [optional] 
**hostname** | **str** |  | [optional] 
**nameservers** | **List[str]** |  | [optional] 
**search_domains** | **List[str]** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_dns import SystemNetworkDNS

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkDNS from a JSON string
system_network_dns_instance = SystemNetworkDNS.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkDNS.to_json())

# convert the object into a dict
system_network_dns_dict = system_network_dns_instance.to_dict()
# create an instance of SystemNetworkDNS from a dict
system_network_dns_from_dict = SystemNetworkDNS.from_dict(system_network_dns_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


