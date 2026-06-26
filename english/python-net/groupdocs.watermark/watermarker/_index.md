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

* [AI agents and LLM integration](/watermark/python-net/guides/agents-and-llm-integration/)
* [Existing objects in diagrams](/watermark/python-net/guides/existing-objects-in-diagram-document/)
* [Email attachments](/watermark/python-net/guides/email-attachments/)
* [Email messages](/watermark/python-net/guides/email-messages/)
* [Adding watermark to images inside a document](/watermark/python-net/guides/adding-watermark-to-images-inside-a-document/)
* [Attachments in PDF document](/watermark/python-net/guides/attachments-in-pdf-document/)
* [Existing objects in PDF document](/watermark/python-net/guides/existing-objects-in-pdf-document/)
* [Rasterize document or page](/watermark/python-net/guides/rasterize-document-or-page/)
* [Watermarks in PDF document](/watermark/python-net/guides/watermarks-in-pdf-document/)
* [Working with slide backgrounds](/watermark/python-net/guides/working-with-slide-backgrounds/)
* [Shapes in spreadsheet document](/watermark/python-net/guides/shapes-in-spreadsheet-document/)
* [Working with spreadsheet document attachments](/watermark/python-net/guides/working-with-spreadsheet-document-attachments/)
* [Working with worksheet backgrounds](/watermark/python-net/guides/working-with-worksheet-backgrounds/)
* [Working with worksheet headers and footers](/watermark/python-net/guides/working-with-worksheet-headers-and-footers/)
* [Existing objects in word processing document](/watermark/python-net/guides/existing-objects-in-word-processing-document/)
* [Locking watermark in word processing document](/watermark/python-net/guides/locking-watermark-in-word-processing-document/)
* [Protecting word processing documents](/watermark/python-net/guides/protecting-word-processing-documents/)
* [Watermarks in word processing document](/watermark/python-net/guides/watermarks-in-word-processing-document/)
* [Adding image watermarks](/watermark/python-net/guides/adding-image-watermarks/)
* [Adding text watermarks](/watermark/python-net/guides/adding-text-watermarks/)
* [Result of added watermarks](/watermark/python-net/guides/result-of-added-watermarks/)
* [Modifying found watermark properties](/watermark/python-net/guides/modifying-found-watermark-properties/)
* [Removing found watermarks](/watermark/python-net/guides/removing-found-watermarks/)
* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)
* [Clear watermarks](/watermark/python-net/guides/clear/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Get document info](/watermark/python-net/guides/get-document-info/)
* [Document preview](/watermark/python-net/guides/preview/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Quick Start Guide](/watermark/python-net/guides/quick-start-guide/)
* [GroupDocs.Watermark for Python via .NET Overview](/watermark/python-net/guides/product-overview/)

### See Also
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
