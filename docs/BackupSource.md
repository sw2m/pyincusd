# BackupSource


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Source type | [optional] 
**url** | **str** | URL of the backup tarball (for url) | [optional] 

## Example

```python
from pyincusd.models.backup_source import BackupSource

# TODO update the JSON string below
json = "{}"
# create an instance of BackupSource from a JSON string
backup_source_instance = BackupSource.from_json(json)
# print the JSON string representation of the object
print(BackupSource.to_json())

# convert the object into a dict
backup_source_dict = backup_source_instance.to_dict()
# create an instance of BackupSource from a dict
backup_source_from_dict = BackupSource.from_dict(backup_source_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


