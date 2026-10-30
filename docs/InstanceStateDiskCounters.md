# InstanceStateDiskCounters

InstanceStateDiskCounters represents I/O counters as part of the disk section of an instance's state.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bytes_read** | **int** | Number of bytes read | [optional] 
**bytes_written** | **int** | Number of bytes written | [optional] 
**reads_completed** | **int** | Number of read operations completed | [optional] 
**writes_completed** | **int** | Number of write operations completed | [optional] 

## Example

```python
from pyincusd.models.instance_state_disk_counters import InstanceStateDiskCounters

# TODO update the JSON string below
json = "{}"
# create an instance of InstanceStateDiskCounters from a JSON string
instance_state_disk_counters_instance = InstanceStateDiskCounters.from_json(json)
# print the JSON string representation of the object
print(InstanceStateDiskCounters.to_json())

# convert the object into a dict
instance_state_disk_counters_dict = instance_state_disk_counters_instance.to_dict()
# create an instance of InstanceStateDiskCounters from a dict
instance_state_disk_counters_from_dict = InstanceStateDiskCounters.from_dict(instance_state_disk_counters_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


