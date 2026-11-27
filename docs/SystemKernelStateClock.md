# SystemKernelStateClock


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**available_sources** | **List[str]** |  | [optional] 
**source** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_kernel_state_clock import SystemKernelStateClock

# TODO update the JSON string below
json = "{}"
# create an instance of SystemKernelStateClock from a JSON string
system_kernel_state_clock_instance = SystemKernelStateClock.from_json(json)
# print the JSON string representation of the object
print(SystemKernelStateClock.to_json())

# convert the object into a dict
system_kernel_state_clock_dict = system_kernel_state_clock_instance.to_dict()
# create an instance of SystemKernelStateClock from a dict
system_kernel_state_clock_from_dict = SystemKernelStateClock.from_dict(system_kernel_state_clock_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


