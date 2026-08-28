# SystemSecurity


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | [**SystemSecurityConfig**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemSecurityConfig.md) |  | [optional] 
**state** | [**SystemSecurityState**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemSecurityState.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_security import SystemSecurity

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSecurity from a JSON string
system_security_instance = SystemSecurity.from_json(json)
# print the JSON string representation of the object
print(SystemSecurity.to_json())

# convert the object into a dict
system_security_dict = system_security_instance.to_dict()
# create an instance of SystemSecurity from a dict
system_security_from_dict = SystemSecurity.from_dict(system_security_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


