# Certificate

Certificate represents a certificate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**certificate** | **str** | The certificate itself, as PEM encoded X509 (or as base64 encoded X509 on POST)  API extension: certificate_self_renewal | [optional] 
**description** | **str** | Certificate description  API extension: certificate_description | [optional] 
**fingerprint** | **str** | SHA256 fingerprint of the certificate | [optional] [readonly] 
**name** | **str** | Name associated with the certificate | [optional] 
**projects** | **List[str]** | List of allowed projects (applies when restricted)  API extension: certificate_project | [optional] 
**restricted** | **bool** | Whether to limit the certificate to listed projects  API extension: certificate_project | [optional] 
**type** | **str** | Usage type for the certificate | [optional] 

## Example

```python
from pyincusd.models.certificate import Certificate

# TODO update the JSON string below
json = "{}"
# create an instance of Certificate from a JSON string
certificate_instance = Certificate.from_json(json)
# print the JSON string representation of the object
print(Certificate.to_json())

# convert the object into a dict
certificate_dict = certificate_instance.to_dict()
# create an instance of Certificate from a dict
certificate_from_dict = Certificate.from_dict(certificate_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


