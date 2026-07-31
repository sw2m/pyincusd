# CertificatesPost202Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**metadata** | [**Operation**](https://github.com/anonhostpi/pyincusd/blob/v7.3.0/docs/Operation.md) |  | [optional] 
**operation** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**status_code** | **int** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.certificates_post202_response import CertificatesPost202Response

# TODO update the JSON string below
json = "{}"
# create an instance of CertificatesPost202Response from a JSON string
certificates_post202_response_instance = CertificatesPost202Response.from_json(json)
# print the JSON string representation of the object
print(CertificatesPost202Response.to_json())

# convert the object into a dict
certificates_post202_response_dict = certificates_post202_response_instance.to_dict()
# create an instance of CertificatesPost202Response from a dict
certificates_post202_response_from_dict = CertificatesPost202Response.from_dict(certificates_post202_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


