---
title: PdfContent
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar ett pdfdokument där en vattenstämpel kan placeras.
type: docs
weight: 610
url: /sv/net/groupdocs.watermark.contents.pdf/pdfcontent/
---
## PdfContent class

Representerar ett pdf-dokument där en vattenstämpel kan placeras.

```csharp
public class PdfContent : Content
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.pdf/pdfcontent/attachments) { get; } | Hämtar samlingen av alla bilagor av detta[`PdfContent`](../pdfcontent) . |
| [PageMarginType](../../groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype) { get; set; } | Hämtar eller ställer in pdf-sidemarginaler som ska användas vid tillägg av vattenstämpel. |
| [Pages](../../groupdocs.watermark.contents.pdf/pdfcontent/pages) { get; } | Hämtar samlingen av alla sidor av detta[`PdfContent`](../pdfcontent) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/decrypt)() | Dekrypterar innehållet. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Tar bort den aktuella instansen. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt)(string) | Krypterar dokumentet med samma lösenord som användarlösenord och ägarlösenord. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt_1)(string, string, PdfPermissions, PdfCryptoAlgorithm) | Krypterar innehållet. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Rasterize](../../groupdocs.watermark.contents.pdf/pdfcontent/rasterize)(int, int, PdfImageConversionFormat) | Konverterar alla innehållssidor till bilder. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenstämplar enligt angivna sökkriterier. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Anmärkningar

**Läs mer:**

* [Lägg till vattenstämplar i PDF-dokument](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
* [Befintliga objekt i PDF-dokument](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
* [Rasterisera dokument eller sida](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
* [Vattenstämplar i pdf-dokument](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

### Se även

* class [Content](../../groupdocs.watermark.contents/content)
* namnutrymme [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
