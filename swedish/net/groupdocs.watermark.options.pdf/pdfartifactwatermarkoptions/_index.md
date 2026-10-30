---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en artefaktvattenstämpel läggs till i ett PDF‑dokument."
type: docs
weight: 1940
url: /sv/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

Representerar alternativ för att lägga till vattenstämpel när en artefaktvattenstämpel läggs till i ett PDF‑dokument.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | Initierar en ny instans av klassen [`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | Hämtar eller anger sidindexet att lägga till vattenstämpeln på. |

### Anmärkningar

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Exempel

Lägg till en bildartefakt‑vattenstämpel i ett PDF-dokument.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### Se även

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
