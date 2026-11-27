# DebugNetworkPing


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**count** | **int** | Number of packets to send, defaults to 10 if unset, 0 pings until the request is canceled. | [optional] 
**family** | **str** | Address family to use, either \&quot;ipv4\&quot; or \&quot;ipv6\&quot;, automatically selected if unset. | [optional] 
**interface** | **str** | Interface to send from, automatically selected if unset. | [optional] 
**interval** | **float** | Seconds to wait between packets. | [optional] 
**numeric** | **bool** | Don&#39;t resolve addresses to names. | [optional] 
**pmtu_discovery** | **str** | Path MTU discovery strategy, one of \&quot;do\&quot;, \&quot;dont\&quot;, \&quot;want\&quot; or \&quot;probe\&quot;. | [optional] 
**size** | **int** | Payload size in bytes. | [optional] 
**target** | **str** | Host name or address to ping. | [optional] 

## Example

```python
from pyincusd.models.debug_network_ping import DebugNetworkPing

# TODO update the JSON string below
json = "{}"
# create an instance of DebugNetworkPing from a JSON string
debug_network_ping_instance = DebugNetworkPing.from_json(json)
# print the JSON string representation of the object
print(DebugNetworkPing.to_json())

# convert the object into a dict
debug_network_ping_dict = debug_network_ping_instance.to_dict()
# create an instance of DebugNetworkPing from a dict
debug_network_ping_from_dict = DebugNetworkPing.from_dict(debug_network_ping_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


