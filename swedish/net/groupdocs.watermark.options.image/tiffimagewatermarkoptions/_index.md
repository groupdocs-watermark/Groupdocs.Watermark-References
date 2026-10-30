---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en vattenstämpel läggs till i en TIFF-bild."
type: docs
weight: 1900
url: /sv/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

Representerar alternativ för att lägga till vattenstämpel när en vattenstämpel läggs till i en TIFF-bild.

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | Initierar en ny instans av klassen [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions). |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | Initierar en ny instans av klassen [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) med ett specificerat index för ramen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Hämtar eller anger index för ramen där vattenstämpeln ska läggas till. |

### Anmärkningar

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Exempel

Lägg till vattenmärke på en specifik ram i en TIFF-bild.

```csharp
TiffImageLoadOptions loadOptions = new TiffImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.tiff", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Se även

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
