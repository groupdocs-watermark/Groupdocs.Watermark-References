---
title: AttachmentWatermarkableImage class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.common/attachmentwatermarkableimage/
is_root: false
weight: 20
---

## AttachmentWatermarkableImage class

Represents an attached image inside a content of any supported type.



**Inheritance:** [`AttachmentWatermarkableImage`](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage) → 
[`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) → 
[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)



The AttachmentWatermarkableImage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage/height) | Gets the height of this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) in pixels. |
| [width](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage/width) | Gets the width of this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) in pixels. |


### Methods
| Method | Description |
| :- | :- |
| [find_images](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage/find_images/#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria) | Finds images according to the specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [find_images](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage/find_images/#) | Finds all images in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage/search/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Finds possible watermarks according to specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage/search/#) | Finds all possible watermarks in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [add](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage/add/#groupdocs.watermark.Watermark) | Adds a watermark to this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage).<br/>This method assumes that watermark offset and size are measured in pixels (if they are assigned). |
| [get_bytes](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage/get_bytes/#) | Gets the image as byte array. |



### See Also
* module [`groupdocs.watermark.common`](..)
* class [`AttachmentWatermarkableImage`](/watermark/python-net/groupdocs.watermark.common/attachmentwatermarkableimage)
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)
* class [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage)
