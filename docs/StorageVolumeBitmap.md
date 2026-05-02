# StorageVolumeBitmap

StorageVolumeBitmap represents a volume bitmap

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**busy** | **bool** | true if the bitmap is in-use by some operation | [optional] 
**count** | **int** | Number of dirty bytes | [optional] 
**granularity** | **int** | Granularity of the dirty bitmap in bytes | [optional] 
**inconsistent** | **bool** | true if this is a persistent bitmap that was improperly stored | [optional] 
**name** | **str** | Bitmap name | [optional] 
**persistent** | **bool** | true if the bitmap was stored on disk, is scheduled to be stored on disk, or both | [optional] 
**recording** | **bool** | true if the bitmap is recording new writes from the guest | [optional] 

## Example

```python
from pyincusd.models.storage_volume_bitmap import StorageVolumeBitmap

# TODO update the JSON string below
json = "{}"
# create an instance of StorageVolumeBitmap from a JSON string
storage_volume_bitmap_instance = StorageVolumeBitmap.from_json(json)
# print the JSON string representation of the object
print(StorageVolumeBitmap.to_json())

# convert the object into a dict
storage_volume_bitmap_dict = storage_volume_bitmap_instance.to_dict()
# create an instance of StorageVolumeBitmap from a dict
storage_volume_bitmap_from_dict = StorageVolumeBitmap.from_dict(storage_volume_bitmap_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


