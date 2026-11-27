# DebugStorageTrace


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**actions** | **List[str]** | I/O categories to trace using blktrace names such as \&quot;discard\&quot; or \&quot;write\&quot;, defaults to all of them. | [optional] 
**device** | **str** | Block device to trace, either a device name or a path under /dev. | [optional] 
**duration** | **int** | Seconds to trace for, defaults to 10 if unset, 0 traces until the request is canceled. | [optional] 

## Example

```python
from pyincusd.models.debug_storage_trace import DebugStorageTrace

# TODO update the JSON string below
json = "{}"
# create an instance of DebugStorageTrace from a JSON string
debug_storage_trace_instance = DebugStorageTrace.from_json(json)
# print the JSON string representation of the object
print(DebugStorageTrace.to_json())

# convert the object into a dict
debug_storage_trace_dict = debug_storage_trace_instance.to_dict()
# create an instance of DebugStorageTrace from a dict
debug_storage_trace_from_dict = DebugStorageTrace.from_dict(debug_storage_trace_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


