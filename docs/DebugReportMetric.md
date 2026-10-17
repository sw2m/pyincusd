# DebugReportMetric


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**fields** | **Dict[str, object]** |  | [optional] 
**name** | **str** |  | [optional] 
**object** | **str** |  | [optional] 
**value** | **object** |  | [optional] 

## Example

```python
from pyincusd.models.debug_report_metric import DebugReportMetric

# TODO update the JSON string below
json = "{}"
# create an instance of DebugReportMetric from a JSON string
debug_report_metric_instance = DebugReportMetric.from_json(json)
# print the JSON string representation of the object
print(DebugReportMetric.to_json())

# convert the object into a dict
debug_report_metric_dict = debug_report_metric_instance.to_dict()
# create an instance of DebugReportMetric from a dict
debug_report_metric_from_dict = DebugReportMetric.from_dict(debug_report_metric_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


