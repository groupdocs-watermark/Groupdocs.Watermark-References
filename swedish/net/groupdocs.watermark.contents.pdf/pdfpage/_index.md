---
title: "PdfPage"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar pdf-dokumentsida."
type: docs
weight: 730
url: /sv/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

Representerar pdf-dokumentsida.

```csharp
public class PdfPage : ContentPart
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | Hämtar samlingen av alla annotationer för denna [`PdfPage`](../pdfpage). |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | Hämtar samlingen av alla artefakter för denna [`PdfPage`](../pdfpage). |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | Hämtar höjden på denna [`PdfPage`](../pdfpage) i punkter. |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | Hämtar bredden på denna [`PdfPage`](../pdfpage) i punkter. |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | Hämtar samlingen av alla XObjects för denna [`PdfPage`](../pdfpage). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | Konverterar sidinnehåll till en bild. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Se även

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
