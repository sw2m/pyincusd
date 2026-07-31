# InstanceNVRAMVariablePut


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attributes** | **List[str]** | Variable attributes. | [optional] 
**data** | **object** | Dissected data. | [optional] 
**timestamp** | **datetime** | Authenticated variable timestamp. | [optional] 

## Example

```python
from pyincusd.models.instance_nvram_variable_put import InstanceNVRAMVariablePut

# TODO update the JSON string below
json = "{}"
# create an instance of InstanceNVRAMVariablePut from a JSON string
instance_nvram_variable_put_instance = InstanceNVRAMVariablePut.from_json(json)
# print the JSON string representation of the object
print(InstanceNVRAMVariablePut.to_json())

# convert the object into a dict
instance_nvram_variable_put_dict = instance_nvram_variable_put_instance.to_dict()
# create an instance of InstanceNVRAMVariablePut from a dict
instance_nvram_variable_put_from_dict = InstanceNVRAMVariablePut.from_dict(instance_nvram_variable_put_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


