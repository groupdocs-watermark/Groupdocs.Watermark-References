---
title: TextWatermark
second_title: GroupDocs.Watermark for .NET API Reference
description: Represents a text watermark.
type: docs
weight: 3270
url: /net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Represents a text watermark.

```csharp
public class TextWatermark : Watermark
```

## Constructors

| Name | Description |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Initializes a new instance of the [`TextWatermark`](../textwatermark) class with a specified text and a font. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Gets or sets the background color of the text. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Gets or sets a value indicating whether the watermark size and coordinates are calculated considering parent margins. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Gets or sets the font of the text. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Gets or sets the foreground color of the text. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Gets or sets the desired height of this [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Gets or sets the horizontal alignment of this [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Gets or sets a value indicating whether the watermark should be placed at background. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Gets or sets the margin settings of this [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Gets or sets the opacity of this [`Watermark`](../../groupdocs.watermark/watermark). |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Gets or sets the padding settings of this [`TextWatermark`](../textwatermark). This property is applicable only to image files. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Gets or sets the pages setup settings of this [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Gets or sets the rotate angle of this [`Watermark`](../../groupdocs.watermark/watermark) in degrees. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Gets or sets a value indicating whether to save information about added watermarks in the document metadata. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Gets or sets a value that defines how watermark size depends on parent size. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Gets or sets a value specifying a way watermark should be sized. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Gets or sets the text to be used as watermark. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Gets or sets the watermark text alignment. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Get or sets options to define repeated watermark |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Gets or sets the vertical alignment of this [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Gets or sets the desired width of this [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Gets or sets the x-coordinate of this [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Gets or sets the y-coordinate of this [`Watermark`](../../groupdocs.watermark/watermark). |

### Remarks

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Examples

Scale the text watermark depending on the parent size.

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### See Also

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
