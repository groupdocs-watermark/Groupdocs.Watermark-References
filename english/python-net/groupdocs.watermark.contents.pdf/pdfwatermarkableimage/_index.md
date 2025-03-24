---
title: PdfWatermarkableImage class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/
is_root: false
weight: 170
---

## PdfWatermarkableImage class

Represents an image inside a Pdf document.



**Inheritance:** [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage) → 
[`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) → 
[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)



The PdfWatermarkableImage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/#bytes) | Initializes a new instance of the [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage) class using specified image data. |


### Properties
| Property | Description |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/height) | Gets the height of this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) in pixels. |
| [width](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/width) | Gets the width of this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage) in pixels. |


### Methods
| Method | Description |
| :- | :- |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/find_images/#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria) | Finds images according to the specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/find_images/#) | Finds all images in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/search/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Finds possible watermarks according to specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/search/#) | Finds all possible watermarks in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [add](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/add/#groupdocs.watermark.Watermark) | Adds a watermark to this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage).<br/>This method assumes that watermark offset and size are measured in pixels (if they are assigned). |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/get_bytes/#) | Gets the image as byte array. |



### See Also
* module [`groupdocs.watermark.contents.pdf`](..)
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage)
* class [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage)
