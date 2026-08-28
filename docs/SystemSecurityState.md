# SystemSecurityState


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**drive_recovery_keys** | **Dict[str, str]** |  | [optional] 
**encrypted_volumes** | [**List[SystemSecurityEncryptedVolume]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemSecurityEncryptedVolume.md) |  | [optional] 
**encryption_recovery_keys_retrieved** | **bool** |  | [optional] 
**pool_recovery_keys** | **Dict[str, str]** |  | [optional] 
**secure_boot_certificates** | [**List[SystemSecuritySecureBootCertificate]**](https://github.com/anonhostpi/pyincusd/blob/v7.4.0/docs/SystemSecuritySecureBootCertificate.md) |  | [optional] 
**secure_boot_enabled** | **bool** |  | [optional] 
**system_state_is_trusted** | **bool** |  | [optional] 
**system_state_status** | **str** |  | [optional] 
**tpm_public_key** | **str** |  | [optional] 
**tpm_status** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.system_security_state import SystemSecurityState

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSecurityState from a JSON string
system_security_state_instance = SystemSecurityState.from_json(json)
# print the JSON string representation of the object
print(SystemSecurityState.to_json())

# convert the object into a dict
system_security_state_dict = system_security_state_instance.to_dict()
# create an instance of SystemSecurityState from a dict
system_security_state_from_dict = SystemSecurityState.from_dict(system_security_state_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


