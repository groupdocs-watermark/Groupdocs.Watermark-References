---
title: Watermarker class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/
is_root: false
weight: 40
---

## Watermarker class

Represents a class for watermark management in a document.



The Watermarker type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#str) | Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified document path. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#str-groupdocs.watermark.options.LoadOptions) | Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified<br/>document path and load options. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#str-groupdocs.watermark.WatermarkerSettings) | Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified<br/>document path and settings. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#str-groupdocs.watermark.options.LoadOptions-groupdocs.watermark.WatermarkerSettings) | Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified<br/>document path, load options and settings. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#io.RawIOBase) | Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified stream. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#io.RawIOBase-groupdocs.watermark.options.LoadOptions) | Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified stream<br/>and load options. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#io.RawIOBase-groupdocs.watermark.WatermarkerSettings) | Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified stream<br/>and settings. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#io.RawIOBase-groupdocs.watermark.options.LoadOptions-groupdocs.watermark.WatermarkerSettings) | Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified stream,<br/>load options and settings. |


### Properties
| Property | Description |
| :- | :- |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects) | Gets or sets the content objects that are to be included in a watermark search. |


### Methods
| Method | Description |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#groupdocs.watermark.Watermark) | Adds a watermark to the loaded document. |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#groupdocs.watermark.Watermark-groupdocs.watermark.options.WatermarkOptions) | Adds a watermark to the loaded document using watermark options. |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#groupdocs.watermark.search.PossibleWatermark) | Removes watermark from the document. |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#groupdocs.watermark.search.PossibleWatermarkCollection) | Removes all watermarks in the collection from the document. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#) | Saves the document data to the underlying stream. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#str) | Saves the document to the specified file location. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#io.RawIOBase) | Saves the document to the specified stream. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#groupdocs.watermark.options.SaveOptions) | Saves the document data to the underlying stream using save options. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#str-groupdocs.watermark.options.SaveOptions) | Saves the document to the specified file location using save options. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#io.RawIOBase-groupdocs.watermark.options.SaveOptions) | Saves the document to the specified stream using save options. |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/#) | Searches all possible watermarks in the document. |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Searches possible watermarks according to specified search criteria. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria) | Finds images according to specified search criteria. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/#) | Finds all images in the document. |
| [get_document_info](/watermark/python-net/groupdocs.watermark/watermarker/get_document_info/#) | Gets the information about the format of the loaded document. |
| [generate_preview](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview/#groupdocs.watermark.options.PreviewOptions) | Generates preview images for the document. |



### Example 


Load and save a content of any supported format.

### See Also
* module [`groupdocs.watermark`](..)
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker)
