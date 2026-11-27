# DebugNetworkTrace


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**count** | **int** | Number of probes to send to each hop, defaults to 10 if unset, 0 traces until the request is canceled. | [optional] 
**family** | **str** | Address family to use, either \&quot;ipv4\&quot; or \&quot;ipv6\&quot;, automatically selected if unset. | [optional] 
**format** | **str** | Output format, either \&quot;json\&quot; (default) or \&quot;text\&quot;. | [optional] 
**interface** | **str** | Interface to send from, automatically selected if unset. | [optional] 
**numeric** | **bool** | Don&#39;t resolve addresses to names. | [optional] 
**target** | **str** | Host name or address to trace the path to. | [optional] 

## Example

```python
from pyincusd.models.debug_network_trace import DebugNetworkTrace

# TODO update the JSON string below
json = "{}"
# create an instance of DebugNetworkTrace from a JSON string
debug_network_trace_instance = DebugNetworkTrace.from_json(json)
# print the JSON string representation of the object
print(DebugNetworkTrace.to_json())

# convert the object into a dict
debug_network_trace_dict = debug_network_trace_instance.to_dict()
# create an instance of DebugNetworkTrace from a dict
debug_network_trace_from_dict = DebugNetworkTrace.from_dict(debug_network_trace_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


