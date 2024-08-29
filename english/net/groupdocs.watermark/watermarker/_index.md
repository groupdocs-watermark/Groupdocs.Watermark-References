---
title: Watermarker
second_title: GroupDocs.Watermark for .NET API Reference
description: Represents a class for watermark management in a document.
type: docs
weight: 3100
url: /net/groupdocs.watermark/watermarker/
---
## Watermarker class

Represents a class for watermark management in a document.

```csharp
public class Watermarker : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Initializes a new instance of the [`Watermarker`](../watermarker) class with the specified stream. |
| [Watermarker](watermarker#constructor_4)(string) | Initializes a new instance of the [`Watermarker`](../watermarker) class with the specified document path. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Initializes a new instance of the [`Watermarker`](../watermarker) class with the specified stream and load options. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Initializes a new instance of the [`Watermarker`](../watermarker) class with the specified stream and settings. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Initializes a new instance of the [`Watermarker`](../watermarker) class with the specified document path and load options. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Initializes a new instance of the [`Watermarker`](../watermarker) class with the specified document path and settings. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Initializes a new instance of the [`Watermarker`](../watermarker) class with the specified stream, load options and settings. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Initializes a new instance of the [`Watermarker`](../watermarker) class with the specified document path, load options and settings. |

## Properties

| Name | Description |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Gets or sets the content objects that are to be included in a watermark search. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Adds a watermark to the loaded document. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Adds a watermark to the loaded document using watermark options. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Disposes the current instance. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Generates preview images for the document. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Returns the [`Content`](../../groupdocs.watermark.contents/content) object for the loaded document. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Gets the information about the format of the loaded document. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Finds all images in the document. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Finds images according to specified search criteria. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Removes watermark from the document. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Removes all watermarks in the collection from the document. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Saves the document data to the underlying stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Saves the document data to the underlying stream using save options. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Saves the document to the specified stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Saves the document to the specified file location. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Saves the document to the specified stream using save options. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Saves the document to the specified file location using save options. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Searches all possible watermarks in the document. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Searches possible watermarks according to specified search criteria. |

### Examples

Load and save a content of any supported format.

```csharp
// Load a content from a file.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Use methods of Watermarker class to add, search or remove watermarks.

    // Save changes.
    watermarker.Save("D:\\output.pdf");
}
```

### See Also

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
