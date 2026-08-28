# SystemNetworkTime


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ntp_servers** | **List[str]** |  | [optional] 
**timezone** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_network_time import SystemNetworkTime

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkTime from a JSON string
system_network_time_instance = SystemNetworkTime.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkTime.to_json())

# convert the object into a dict
system_network_time_dict = system_network_time_instance.to_dict()
# create an instance of SystemNetworkTime from a dict
system_network_time_from_dict = SystemNetworkTime.from_dict(system_network_time_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


