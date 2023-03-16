---
title: WatermarkableImage
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar en bild inuti ett dokument.
type: docs
weight: 420
url: /sv/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

Representerar en bild inuti ett dokument.

```csharp
public abstract class WatermarkableImage : ContentPart
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Får höjden på detta[`WatermarkableImage`](../watermarkableimage) i pixlar. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Får bredden på detta[`WatermarkableImage`](../watermarkableimage) i pixlar. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Lägger till en vattenstämpel till detta[`WatermarkableImage`](../watermarkableimage). Den här metoden förutsätter att vattenmärkesförskjutning och storlek mäts i pixlar (om de är tilldelade). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Hämtar bilden som byte-array. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenstämplar enligt angivna sökkriterier. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Anmärkningar

**Läs mer:**

* [Lägga till vattenstämpel till bilder i ett dokument](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### Exempel

Lägg till vattenstämpel till alla bilder i ett dokument av vilken typ som helst.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Initiera text- eller bildvattenstämpel.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Hitta alla bilder i innehållet.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Lägg till vattenstämpel.
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
* namnutrymme [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->