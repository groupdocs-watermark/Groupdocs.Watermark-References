---
title: "WordProcessingHeaderFooter"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar ett sidhuvud/sidfot i ett Word-dokument."
type: docs
weight: 1360
url: /sv/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/
---
## WordProcessingHeaderFooter class

Representerar ett sidhuvud/sidfot i ett Word-dokument.

```csharp
public class WordProcessingHeaderFooter : ContentPart
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [HeaderFooterType](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/headerfootertype) { get; } | Hämtar typen av detta [`WordProcessingHeaderFooter`](../wordprocessingheaderfooter). |
| [IsLinkedToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/islinkedtoprevious) { get; set; } | Hämtar eller anger ett värde som indikerar om detta header/footer är länkat till motsvarande header/footer i föregående sektion. |
| [Section](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/section) { get; } | Hämtar föräldrasektionen för detta [`WordProcessingHeaderFooter`](../wordprocessingheaderfooter). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Se även

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
