# StorageVolumeBitmapsPost

StorageVolumeBitmapsPost represents the fields available for a new volume bitmap

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**disabled** | **bool** | The bitmap is created in the disabled state | [optional] 
**granularity** | **int** | Granularity of the dirty bitmap in bytes | [optional] 
**name** | **str** | Bitmap name | [optional] 
**persistent** | **bool** | true if the bitmap was stored on disk, is scheduled to be stored on disk, or both | [optional] 

## Example

```python
from pyincusd.models.storage_volume_bitmaps_post import StorageVolumeBitmapsPost

# TODO update the JSON string below
json = "{}"
# create an instance of StorageVolumeBitmapsPost from a JSON string
storage_volume_bitmaps_post_instance = StorageVolumeBitmapsPost.from_json(json)
# print the JSON string representation of the object
print(StorageVolumeBitmapsPost.to_json())

# convert the object into a dict
storage_volume_bitmaps_post_dict = storage_volume_bitmaps_post_instance.to_dict()
# create an instance of StorageVolumeBitmapsPost from a dict
storage_volume_bitmaps_post_from_dict = StorageVolumeBitmapsPost.from_dict(storage_volume_bitmaps_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


