# SystemNextBootVersion


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**next_boot_version** | **str** | If not specified or \&quot;newest\&quot;, the system will attempt to boot into the newest installed OS version. Values of \&quot;current\&quot; or \&quot;oldest\&quot; will change the boot target to reboot into the same version or the prior installed version. | [optional] 

## Example

```python
from pyincusd.models.system_next_boot_version import SystemNextBootVersion

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNextBootVersion from a JSON string
system_next_boot_version_instance = SystemNextBootVersion.from_json(json)
# print the JSON string representation of the object
print(SystemNextBootVersion.to_json())

# convert the object into a dict
system_next_boot_version_dict = system_next_boot_version_instance.to_dict()
# create an instance of SystemNextBootVersion from a dict
system_next_boot_version_from_dict = SystemNextBootVersion.from_dict(system_next_boot_version_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


