# InstanceNvramGuidGetRecursion1200Response

Sync response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**metadata** | [**Dict[str, InstanceNVRAMVariable]**](https://github.com/anonhostpi/pyincusd/blob/v7.3.0/docs/InstanceNVRAMVariable.md) | Namespaced UEFI variables | [optional] 
**status** | **str** | Status description | [optional] 
**status_code** | **int** | Status code | [optional] 
**type** | **str** | Response type | [optional] 

## Example

```python
from pyincusd.models.instance_nvram_guid_get_recursion1200_response import InstanceNvramGuidGetRecursion1200Response

# TODO update the JSON string below
json = "{}"
# create an instance of InstanceNvramGuidGetRecursion1200Response from a JSON string
instance_nvram_guid_get_recursion1200_response_instance = InstanceNvramGuidGetRecursion1200Response.from_json(json)
# print the JSON string representation of the object
print(InstanceNvramGuidGetRecursion1200Response.to_json())

# convert the object into a dict
instance_nvram_guid_get_recursion1200_response_dict = instance_nvram_guid_get_recursion1200_response_instance.to_dict()
# create an instance of InstanceNvramGuidGetRecursion1200Response from a dict
instance_nvram_guid_get_recursion1200_response_from_dict = InstanceNvramGuidGetRecursion1200Response.from_dict(instance_nvram_guid_get_recursion1200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


