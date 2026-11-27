# DebugNetworkDumpTraffic


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**duration** | **int** | Seconds to capture for, defaults to 10 if unset, 0 captures until the request is canceled. | [optional] 
**filter** | **str** | Capture filter expression in tcpdump syntax. | [optional] 
**format** | **str** | Output format, either \&quot;text\&quot; (default) or \&quot;pcap\&quot;. | [optional] 
**interface** | **str** | Interface to capture on, defaults to all interfaces. | [optional] 

## Example

```python
from pyincusd.models.debug_network_dump_traffic import DebugNetworkDumpTraffic

# TODO update the JSON string below
json = "{}"
# create an instance of DebugNetworkDumpTraffic from a JSON string
debug_network_dump_traffic_instance = DebugNetworkDumpTraffic.from_json(json)
# print the JSON string representation of the object
print(DebugNetworkDumpTraffic.to_json())

# convert the object into a dict
debug_network_dump_traffic_dict = debug_network_dump_traffic_instance.to_dict()
# create an instance of DebugNetworkDumpTraffic from a dict
debug_network_dump_traffic_from_dict = DebugNetworkDumpTraffic.from_dict(debug_network_dump_traffic_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


