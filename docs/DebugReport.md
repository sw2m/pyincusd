# DebugReport


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**media_type** | **str** |  | [optional] 
**metrics** | [**List[DebugReportMetric]**](https://github.com/anonhostpi/pyincusd/blob/v7.0.2.post12/docs/DebugReportMetric.md) |  | [optional] 
**timestamp** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.debug_report import DebugReport

# TODO update the JSON string below
json = "{}"
# create an instance of DebugReport from a JSON string
debug_report_instance = DebugReport.from_json(json)
# print the JSON string representation of the object
print(DebugReport.to_json())

# convert the object into a dict
debug_report_dict = debug_report_instance.to_dict()
# create an instance of DebugReport from a dict
debug_report_from_dict = DebugReport.from_dict(debug_report_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


