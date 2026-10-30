---
title: "PresentationWatermarkableImage"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en bild i ett PowerPoint-dokument."
type: docs
weight: 1090
url: /sv/net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/
---
## PresentationWatermarkableImage class

Representerar en bild i ett PowerPoint-dokument.

```csharp
public class PresentationWatermarkableImage : WatermarkableImage
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PresentationWatermarkableImage](presentationwatermarkableimage)(byte[]) | Initierar en ny instans av klassen [`PresentationWatermarkableImage`](../presentationwatermarkableimage) med angivna bilddata. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Hämtar höjden på denna [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) i pixlar. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Hämtar bredden på denna [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) i pixlar. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Lägger till en vattenstämpel på denna [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage). Denna metod förutsätter att vattenstämpelns offset och storlek mäts i pixlar (om de har tilldelats). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Hämtar bilden som bytearray. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Se även

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
