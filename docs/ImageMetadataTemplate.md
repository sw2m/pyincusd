# ImageMetadataTemplate

ImageMetadataTemplate represents a template entry in image metadata (used in image tarball)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**create_only** | **bool** | Whether to trigger only if the file is missing | [optional] 
**gid** | **str** | The file owner gid.  API extension: image_template_permissions | [optional] 
**mode** | **str** | The file permissions.  API extension: image_template_permissions | [optional] 
**properties** | **Dict[str, str]** | Key/value properties to pass to the template | [optional] 
**template** | **str** | The template itself as a valid pongo2 template | [optional] 
**uid** | **str** | The file owner uid.  API extension: image_template_permissions | [optional] 
**when** | **List[str]** | When to trigger the template (create, copy or start) | [optional] 

## Example

```python
from pyincusd.models.image_metadata_template import ImageMetadataTemplate

# TODO update the JSON string below
json = "{}"
# create an instance of ImageMetadataTemplate from a JSON string
image_metadata_template_instance = ImageMetadataTemplate.from_json(json)
# print the JSON string representation of the object
print(ImageMetadataTemplate.to_json())

# convert the object into a dict
image_metadata_template_dict = image_metadata_template_instance.to_dict()
# create an instance of ImageMetadataTemplate from a dict
image_metadata_template_from_dict = ImageMetadataTemplate.from_dict(image_metadata_template_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


