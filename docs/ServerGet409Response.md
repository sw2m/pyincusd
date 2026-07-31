# ServerGet409Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**error** | **str** |  | [optional] 
**error_code** | **int** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from pyincusd.models.server_get409_response import ServerGet409Response

# TODO update the JSON string below
json = "{}"
# create an instance of ServerGet409Response from a JSON string
server_get409_response_instance = ServerGet409Response.from_json(json)
# print the JSON string representation of the object
print(ServerGet409Response.to_json())

# convert the object into a dict
server_get409_response_dict = server_get409_response_instance.to_dict()
# create an instance of ServerGet409Response from a dict
server_get409_response_from_dict = ServerGet409Response.from_dict(server_get409_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


