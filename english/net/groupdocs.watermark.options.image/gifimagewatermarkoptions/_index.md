---
title: GifImageWatermarkOptions
second_title: GroupDocs.Watermark for .NET API Reference
description: Represents watermark adding options when adding watermark to a GIF image.
type: docs
weight: 1800
url: /net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

Represents watermark adding options when adding watermark to a GIF image.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | Initializes a new instance of the [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) class. |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | Initializes a new instance of the [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) class with a specified index of a frame. |

## Properties

| Name | Description |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Gets or sets the index of frame to add watermark. |

### Remarks

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Examples

Add a watermark to a particular frame of GIF image.

```csharp
GifImageLoadOptions loadOptions = new GifImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### See Also

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
