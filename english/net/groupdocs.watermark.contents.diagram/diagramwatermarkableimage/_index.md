---
title: DiagramWatermarkableImage
second_title: GroupDocs.Watermark for .NET API Reference
description: Represents an image inside a Visio document.
type: docs
weight: 260
url: /net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/
---
## DiagramWatermarkableImage class

Represents an image inside a Visio document.

```csharp
public class DiagramWatermarkableImage : WatermarkableImage
```

## Constructors

| Name | Description |
| --- | --- |
| [DiagramWatermarkableImage](diagramwatermarkableimage)(byte[]) | Initializes a new instance of the [`DiagramWatermarkableImage`](../diagramwatermarkableimage) class using specified image data. |

## Properties

| Name | Description |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Gets the height of this [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in pixels. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Gets the width of this [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in pixels. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Adds a watermark to this [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage). This method assumes that watermark offset and size are measured in pixels (if they are assigned). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Finds all images in the content. The search is conducted in the objects specified in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Finds images according to the specified search criteria. The search is conducted in the objects specified in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Gets the image as byte array. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Finds all possible watermarks in the content. The search is conducted in the objects specified in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Finds possible watermarks according to specified search criteria. The search is conducted in the objects specified in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### See Also

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents.Diagram](../../groupdocs.watermark.contents.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->