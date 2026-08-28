# SystemSecuritySecureBootCertificate


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**fingerprint** | **str** |  | [optional] 
**issuer** | **str** |  | [optional] 
**subject** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_security_secure_boot_certificate import SystemSecuritySecureBootCertificate

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSecuritySecureBootCertificate from a JSON string
system_security_secure_boot_certificate_instance = SystemSecuritySecureBootCertificate.from_json(json)
# print the JSON string representation of the object
print(SystemSecuritySecureBootCertificate.to_json())

# convert the object into a dict
system_security_secure_boot_certificate_dict = system_security_secure_boot_certificate_instance.to_dict()
# create an instance of SystemSecuritySecureBootCertificate from a dict
system_security_secure_boot_certificate_from_dict = SystemSecuritySecureBootCertificate.from_dict(system_security_secure_boot_certificate_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


