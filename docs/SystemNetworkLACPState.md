# SystemNetworkLACPState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**local_mac** | **str** |  | [optional] 
**remote_mac** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_lacp_state import SystemNetworkLACPState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkLACPState from a JSON string
system_network_lacp_state_instance = SystemNetworkLACPState.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkLACPState.to_json())

# convert the object into a dict
system_network_lacp_state_dict = system_network_lacp_state_instance.to_dict()
# create an instance of SystemNetworkLACPState from a dict
system_network_lacp_state_from_dict = SystemNetworkLACPState.from_dict(system_network_lacp_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


