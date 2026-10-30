---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en vattenstämpel läggs till en multiram bild."
type: docs
weight: 1870
url: /sv/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

Representerar alternativ för att lägga till vattenstämpel när en vattenstämpel läggs till i en bild med flera ramar.

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | Initierar en ny instans av klassen [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions). |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | Initierar en ny instans av klassen [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) med ett angivet index för ramen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Hämtar eller anger index för ramen där vattenstämpeln ska läggas till. |

### Anmärkningar

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Exempel

Lägg till vattenstämpel på en specifik ram i en multi-ram bild.

```csharp
ImageLoadOptions loadOptions = new ImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Se även

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
