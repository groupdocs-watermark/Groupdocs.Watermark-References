---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en bild i ett dokument."
type: docs
weight: 470
url: /sv/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

Representerar en bild i ett dokument.

```csharp
public abstract class WatermarkableImage : ContentPart
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Hämtar höjden på denna [`WatermarkableImage`](../watermarkableimage) i pixlar. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Hämtar bredden på denna [`WatermarkableImage`](../watermarkableimage) i pixlar. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Lägger till ett vattenmärke på denna [`WatermarkableImage`](../watermarkableimage). Denna metod förutsätter att vattenmärkesförskjutning och storlek mäts i pixlar (om de har tilldelats). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Hämtar bilden som bytearray. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Anmärkningar

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### Exempel

Lägg till vattenmärke på alla bilder i ett dokument av någon stödd typ.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Initiera text- eller bildvattenmärke.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Hitta alla bilder i innehållet.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Lägg till vattenmärke.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // Spara ändringar.
    watermarker.Save(@"D:\output.doc");
}
```

### Se även

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
