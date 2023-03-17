---
title: PdfAnnotationWatermarkOptions
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt opties voor het toevoegen van watermerken bij het toevoegen van een annotatiewatermerk aan een pdfdocument.
type: docs
weight: 1860
url: /nl/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

Vertegenwoordigt opties voor het toevoegen van watermerken bij het toevoegen van een annotatiewatermerk aan een pdf-document.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | Initialiseert een nieuw exemplaar van het[`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | Haalt de pagina-index op of stelt deze in om een watermerk aan toe te voegen. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | Ontvang of stel de waarde in die aangeeft of annotatie wordt afgedrukt, maar niet wordt weergegeven in pdf-weergavetoepassing. |

### Opmerkingen

**Kom meer te weten:**

* [Voeg watermerken toe aan PDF-documenten](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Voorbeelden

Voeg een watermerk voor afbeeldingsannotaties toe aan een PDF-document.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // standaard - alle pagina's

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### Zie ook

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* naamruimte [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->