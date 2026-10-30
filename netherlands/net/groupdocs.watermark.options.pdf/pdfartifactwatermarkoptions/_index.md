---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor wanneer een artefactwatermerk aan een pdf‑document wordt toegevoegd."
type: docs
weight: 1940
url: /nl/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

Stelt opties voor het toevoegen van een watermerk voor wanneer een artefactwatermerk aan een pdf‑document wordt toegevoegd.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | Initialiseert een nieuw exemplaar van de [`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | Gets of sets het paginanummer waarop het watermerk moet worden toegevoegd. |

### Opmerkingen

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Voorbeelden

Voeg een afbeelding artefact-watermerk toe aan een PDF-document.

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

### Zie ook

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
