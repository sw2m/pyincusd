# SystemSecurityEncryptedVolume


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**state** | **str** |  | [optional] 
**volume** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_security_encrypted_volume import SystemSecurityEncryptedVolume

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSecurityEncryptedVolume from a JSON string
system_security_encrypted_volume_instance = SystemSecurityEncryptedVolume.from_json(json)
# print the JSON string representation of the object
print(SystemSecurityEncryptedVolume.to_json())

# convert the object into a dict
system_security_encrypted_volume_dict = system_security_encrypted_volume_instance.to_dict()
# create an instance of SystemSecurityEncryptedVolume from a dict
system_security_encrypted_volume_from_dict = SystemSecurityEncryptedVolume.from_dict(system_security_encrypted_volume_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


