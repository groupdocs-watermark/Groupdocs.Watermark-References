---
title: PresentationWatermarkableImage class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/
is_root: false
weight: 230
---

## PresentationWatermarkableImage class

Represents an image inside a PowerPoint document.



**Inheritance:** [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage) → 
[`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) → 
[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)



The PresentationWatermarkableImage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/#bytes) | Initializes a new instance of the [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage)<br/>class using specified image data. |


### Properties
| Property | Description |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/height) | Gets the height of this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) in pixels. |
| [width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/width) | Gets the width of this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) in pixels. |


### Methods
| Method | Description |
| :- | :- |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/find_images/#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria) | Finds images according to the specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/find_images/#) | Finds all images in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/search/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Finds possible watermarks according to specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/search/#) | Finds all possible watermarks in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [add](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/add/#groupdocs.watermark.Watermark) | Adds a watermark to this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage).<br/>This method assumes that watermark offset and size are measured in pixels (if they are assigned). |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/get_bytes/#) | Gets the image as byte array. |



### See Also
* module [`groupdocs.watermark.contents.presentation`](..)
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage)
* class [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage)
