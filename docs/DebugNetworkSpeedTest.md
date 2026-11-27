# DebugNetworkSpeedTest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bitrate** | **str** | Target bitrate in bits per second with an optional K, M or G suffix, 0 for unlimited. | [optional] 
**duration** | **int** | Seconds to test for, defaults to 10 if unset, 0 tests until the request is canceled. | [optional] 
**family** | **str** | Address family to use, either \&quot;ipv4\&quot; or \&quot;ipv6\&quot;, automatically selected if unset. | [optional] 
**format** | **str** | Output format, either \&quot;json\&quot; (default) or \&quot;text\&quot;. | [optional] 
**interface** | **str** | Interface to send from, automatically selected if unset. | [optional] 
**parallel** | **int** | Number of parallel connections to test with, defaults to 1. | [optional] 
**port** | **int** | Port of the iperf3 server, defaults to 5201. | [optional] 
**protocol** | **str** | Protocol to test with, either \&quot;tcp\&quot; (default) or \&quot;udp\&quot;. | [optional] 
**reverse** | **bool** | Measure the download rather than upload bandwidth. | [optional] 
**target** | **str** | Host name or address of the iperf3 server. | [optional] 

## Example

```python
from pyincusd.models.debug_network_speed_test import DebugNetworkSpeedTest

# TODO update the JSON string below
json = "{}"
# create an instance of DebugNetworkSpeedTest from a JSON string
debug_network_speed_test_instance = DebugNetworkSpeedTest.from_json(json)
# print the JSON string representation of the object
print(DebugNetworkSpeedTest.to_json())

# convert the object into a dict
debug_network_speed_test_dict = debug_network_speed_test_instance.to_dict()
# create an instance of DebugNetworkSpeedTest from a dict
debug_network_speed_test_from_dict = DebugNetworkSpeedTest.from_dict(debug_network_speed_test_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


