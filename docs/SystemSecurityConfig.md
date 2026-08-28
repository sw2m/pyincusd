# SystemSecurityConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_ca_certs** | **List[str]** |  | [optional] 
**encryption_recovery_keys** | **List[str]** |  | [optional] 

## Example

```python
from pyincusd.models.system_security_config import SystemSecurityConfig

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSecurityConfig from a JSON string
system_security_config_instance = SystemSecurityConfig.from_json(json)
# print the JSON string representation of the object
print(SystemSecurityConfig.to_json())

# convert the object into a dict
system_security_config_dict = system_security_config_instance.to_dict()
# create an instance of SystemSecurityConfig from a dict
system_security_config_from_dict = SystemSecurityConfig.from_dict(system_security_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


