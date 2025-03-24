---
title: WordProcessingWatermarkableImage class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/
is_root: false
weight: 130
---

## WordProcessingWatermarkableImage class

Represents an image inside a Word document.



**Inheritance:** [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage) → 
[`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) → 
[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)



The WordProcessingWatermarkableImage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/__init__/#bytes) | Initializes a new instance of the [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage) class using specified image data. |


### Properties
| Property | Description |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/height) | Gets the height of this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) in pixels. |
| [width](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/width) | Gets the width of this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) in pixels. |


### Methods
| Method | Description |
| :- | :- |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/find_images/#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria) | Finds images according to the specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/find_images/#) | Finds all images in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/search/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Finds possible watermarks according to specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/search/#) | Finds all possible watermarks in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [add](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/add/#groupdocs.watermark.Watermark) | Adds a watermark to this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage).<br/>This method assumes that watermark offset and size are measured in pixels (if they are assigned). |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/get_bytes/#) | Gets the image as byte array. |



### See Also
* module [`groupdocs.watermark.contents.wordprocessing`](..)
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)
* class [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage)
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage)
