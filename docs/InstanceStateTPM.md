# InstanceStateTPM


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**endorsement_keys** | [**List[InstanceStateTPMKey]**](https://github.com/anonhostpi/pyincusd/blob/v7.6.0/docs/InstanceStateTPMKey.md) | Endorsement keys, when known. | [optional] 

## Example

```python
from pyincusd.models.instance_state_tpm import InstanceStateTPM

# TODO update the JSON string below
json = "{}"
# create an instance of InstanceStateTPM from a JSON string
instance_state_tpm_instance = InstanceStateTPM.from_json(json)
# print the JSON string representation of the object
print(InstanceStateTPM.to_json())

# convert the object into a dict
instance_state_tpm_dict = instance_state_tpm_instance.to_dict()
# create an instance of InstanceStateTPM from a dict
instance_state_tpm_from_dict = InstanceStateTPM.from_dict(instance_state_tpm_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


