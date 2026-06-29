---
title: Watermarker class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents a class for watermark management in a document."
type: docs
url: /python-net/groupdocs.watermark/watermarker/
is_root: false
weight: 180
---


## Watermarker class

Represents a class for watermark management in a document.

The Watermarker type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path) | Initializes a new Watermarker instance with the specified document path. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options) | Initializes a new Watermarker instance with the specified document path and load options. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-settings) | Initializes a new Watermarker instance with the specified document path and settings. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options-settings) | Initializes a new Watermarker with the specified document path, load options, and settings. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document) | Initializes a new Watermarker instance with the specified stream. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options) | Initializes a new instance of the Watermarker class with the specified stream and load options. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-settings) | Initializes a new instance of the Watermarker class with the specified stream and settings. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options-settings) | Initializes a new Watermarker instance with the specified document stream, load options, and settings. |

### Methods
| Method | Description |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark) | Adds a watermark to the loaded document. |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark-options) | Adds a watermark to the loaded document using watermark options. |
| [add_watermark](/watermark/python-net/groupdocs.watermark/watermarker/add_watermark/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark/watermarker/dispose/) | Disposes the current instance. |
| [generate_preview](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview/#preview_options) | Generates preview images for the document. |
| [generate_preview_preview_options](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview_preview_options/) |  |
| [get_content](/watermark/python-net/groupdocs.watermark/watermarker/get_content/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark/watermarker/get_document_info/) | Gets the information about the format of the loaded document. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/#search_criteria) | Finds images according to the specified search criteria. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/) | Finds all images in the document. |
| [get_images_image_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/get_images_image_search_criteria/) |  |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermark) | Removes watermark from the document. |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermarks) | Removes all watermarks in the collection from the document. |
| [remove_possible_watermark](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark/) |  |
| [remove_possible_watermark_collection](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark_collection/) |  |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/) | Saves the document data to the underlying stream. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path) | Saves the document to the specified file location. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document) | Saves the document to the specified stream. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#options) | Saves the document data to the underlying stream using the specified save options. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path-options) | Saves the document to the specified file location using save options. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document-options) | Saves the document to the specified stream using save options. |
| [save_file](/watermark/python-net/groupdocs.watermark/watermarker/save_file/) |  |
| [save_save_options](/watermark/python-net/groupdocs.watermark/watermarker/save_save_options/) |  |
| [save_stream](/watermark/python-net/groupdocs.watermark/watermarker/save_stream/) |  |
| [save_streams](/watermark/python-net/groupdocs.watermark/watermarker/save_streams/) |  |
| [save_string](/watermark/python-net/groupdocs.watermark/watermarker/save_string/) |  |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/) | Searches all possible watermarks in the document. |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/#search_criteria) | Searches possible watermarks according to specified search criteria. |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/search_search_criteria/) |  |

### Properties
| Property | Description |
| :- | :- |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) | The objects that are to be included in a watermark search. |

### Example

```python
import groupdocs.watermark as gw

with gw.Watermarker("D:\\input.pdf") as watermarker:
    # Use methods of Watermarker to add, search, or remove watermarks.
    watermarker.save("D:\\output.pdf")
```

### Guides
Task guides that use `Watermarker`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)
* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)
* [Document preview](/watermark/python-net/guides/preview/)
* [Get document info](/watermark/python-net/guides/get-document-info/)

### See Also
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
