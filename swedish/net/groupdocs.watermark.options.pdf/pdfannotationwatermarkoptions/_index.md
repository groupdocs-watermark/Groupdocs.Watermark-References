---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en annoteringsvattenstämpel läggs till i ett PDF‑dokument."
type: docs
weight: 1930
url: /sv/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

Representerar alternativ för att lägga till vattenstämpel när en annoteringsvattenstämpel läggs till i ett PDF‑dokument.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | Initierar en ny instans av klassen [`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | Hämtar eller anger sidindexet att lägga till vattenstämpeln på. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | Hämtar eller anger värdet som indikerar om annotationen ska skrivas ut, men inte visas i PDF‑visningsprogrammet. |

### Anmärkningar

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Exempel

Lägg till en bild‑annotation‑vattenstämpel i ett PDF-dokument.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### Se även

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
