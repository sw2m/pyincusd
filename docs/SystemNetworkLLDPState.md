# SystemNetworkLLDPState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chassis_id** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**port** | **str** |  | [optional] 
**port_id** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_lldp_state import SystemNetworkLLDPState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkLLDPState from a JSON string
system_network_lldp_state_instance = SystemNetworkLLDPState.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkLLDPState.to_json())

# convert the object into a dict
system_network_lldp_state_dict = system_network_lldp_state_instance.to_dict()
# create an instance of SystemNetworkLLDPState from a dict
system_network_lldp_state_from_dict = SystemNetworkLLDPState.from_dict(system_network_lldp_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


