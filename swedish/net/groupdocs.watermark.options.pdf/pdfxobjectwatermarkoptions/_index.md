---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en XObject‑vattenstämpel läggs till i ett PDF‑dokument."
type: docs
weight: 1990
url: /sv/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

Representerar alternativ för att lägga till vattenstämpel när en XObject‑vattenstämpel läggs till i ett PDF‑dokument.

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | Initierar en ny instans av klassen [`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | Hämtar eller anger sidindexet att lägga till vattenstämpeln på. |

### Anmärkningar

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Exempel

Lägg till en vattenstämpel på en specifik sida i ett PDF-dokument.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Se även

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
