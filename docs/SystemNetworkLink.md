# SystemNetworkLink


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Interface name, or MAC address or device name of an interface or bond member | [optional] 
**state** | **str** | Either \&quot;up\&quot; or \&quot;down\&quot; | [optional] 

## Example

```python
from pyincusd.models.system_network_link import SystemNetworkLink

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkLink from a JSON string
system_network_link_instance = SystemNetworkLink.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkLink.to_json())

# convert the object into a dict
system_network_link_dict = system_network_link_instance.to_dict()
# create an instance of SystemNetworkLink from a dict
system_network_link_from_dict = SystemNetworkLink.from_dict(system_network_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


