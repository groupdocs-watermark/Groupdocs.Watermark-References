---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor wanneer een annotatiewatermerk aan een pdf‑document wordt toegevoegd."
type: docs
weight: 1930
url: /nl/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

Stelt opties voor het toevoegen van een watermerk voor wanneer een annotatiewatermerk aan een pdf‑document wordt toegevoegd.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | Initialiseert een nieuw exemplaar van de [`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | Gets of sets het paginanummer waarop het watermerk moet worden toegevoegd. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | Gets of sets de waarde die aangeeft of annotatie wordt afgedrukt, maar niet wordt weergegeven in een pdf-weergaveapplicatie. |

### Opmerkingen

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Voorbeelden

Voeg een afbeelding annotatie-watermerk toe aan een PDF-document.

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

### Zie ook

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
