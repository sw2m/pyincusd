# InstancePortForwardPost


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | Address to connect to inside of the instance | [optional] 
**port** | **int** | TCP port to connect to inside of the instance | [optional] 

## Example

```python
from pyincusd.models.instance_port_forward_post import InstancePortForwardPost

# TODO update the JSON string below
json = "{}"
# create an instance of InstancePortForwardPost from a JSON string
instance_port_forward_post_instance = InstancePortForwardPost.from_json(json)
# print the JSON string representation of the object
print(InstancePortForwardPost.to_json())

# convert the object into a dict
instance_port_forward_post_dict = instance_port_forward_post_instance.to_dict()
# create an instance of InstancePortForwardPost from a dict
instance_port_forward_post_from_dict = InstancePortForwardPost.from_dict(instance_port_forward_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


