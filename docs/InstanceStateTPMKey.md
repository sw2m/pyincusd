# InstanceStateTPMKey


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**fingerprint** | **str** | SHA-256 fingerprint of the DER encoded public key. | [optional] 
**public_key** | **str** | PEM encoded public key. | [optional] 
**size** | **int** | Key size in bits. | [optional] 
**type** | **str** | Key type (&#x60;rsa&#x60; or &#x60;ecc&#x60;). | [optional] 

## Example

```python
from pyincusd.models.instance_state_tpm_key import InstanceStateTPMKey

# TODO update the JSON string below
json = "{}"
# create an instance of InstanceStateTPMKey from a JSON string
instance_state_tpm_key_instance = InstanceStateTPMKey.from_json(json)
# print the JSON string representation of the object
print(InstanceStateTPMKey.to_json())

# convert the object into a dict
instance_state_tpm_key_dict = instance_state_tpm_key_instance.to_dict()
# create an instance of InstanceStateTPMKey from a dict
instance_state_tpm_key_from_dict = InstanceStateTPMKey.from_dict(instance_state_tpm_key_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


