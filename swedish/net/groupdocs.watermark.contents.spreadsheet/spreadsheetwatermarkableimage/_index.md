---
title: SpreadsheetWatermarkableImage
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar en bild inuti ett Exceldokument.
type: docs
weight: 1250
url: /sv/net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/
---
## SpreadsheetWatermarkableImage class

Representerar en bild inuti ett Excel-dokument.

```csharp
public class SpreadsheetWatermarkableImage : WatermarkableImage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SpreadsheetWatermarkableImage](spreadsheetwatermarkableimage)(byte[]) | Initierar en ny instans av[`SpreadsheetWatermarkableImage`](../spreadsheetwatermarkableimage) class med angivna bilddata. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Får höjden på detta[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) i pixlar. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Får bredden på detta[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) i pixlar. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Lägger till en vattenstämpel till detta[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage). Den här metoden förutsätter att vattenmärkesförskjutning och storlek mäts i pixlar (om de är tilldelade). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Hämtar bilden som byte-array. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenstämplar enligt angivna sökkriterier. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Se även

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namnutrymme [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->