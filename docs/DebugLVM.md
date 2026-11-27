# DebugLVM


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lvs** | **List[Dict[str, object]]** |  | [optional] 
**pvs** | **List[Dict[str, object]]** |  | [optional] 
**vgs** | **List[Dict[str, object]]** |  | [optional] 

## Example

```python
from pyincusd.models.debug_lvm import DebugLVM

# TODO update the JSON string below
json = "{}"
# create an instance of DebugLVM from a JSON string
debug_lvm_instance = DebugLVM.from_json(json)
# print the JSON string representation of the object
print(DebugLVM.to_json())

# convert the object into a dict
debug_lvm_dict = debug_lvm_instance.to_dict()
# create an instance of DebugLVM from a dict
debug_lvm_from_dict = DebugLVM.from_dict(debug_lvm_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


