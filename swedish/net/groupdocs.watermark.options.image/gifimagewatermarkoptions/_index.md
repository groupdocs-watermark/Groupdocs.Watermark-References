---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel vid tillägg till en GIF-bild."
type: docs
weight: 1830
url: /sv/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

Representerar alternativ för att lägga till vattenstämpel vid tillägg till en GIF-bild.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | Initierar en ny instans av klassen [`GifImageWatermarkOptions`](../gifimagewatermarkoptions). |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | Initierar en ny instans av klassen [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) med ett angivet index för en ram. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Hämtar eller anger index för ramen där vattenstämpeln ska läggas till. |

### Anmärkningar

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Exempel

Lägg till ett vattenmärke på en specifik ram i en GIF-bild.

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

### Se även

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
