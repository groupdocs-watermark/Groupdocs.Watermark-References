---
title: PdfXObjectWatermarkOptions
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt opties voor het toevoegen van watermerken bij het toevoegen van een XObjectwatermerk aan een pdfdocument.
type: docs
weight: 1920
url: /nl/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

Vertegenwoordigt opties voor het toevoegen van watermerken bij het toevoegen van een XObject-watermerk aan een pdf-document.

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | Initialiseert een nieuw exemplaar van het[`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | Haalt de pagina-index op of stelt deze in om een watermerk aan toe te voegen. |

### Opmerkingen

**Kom meer te weten:**

* [Voeg watermerken toe aan PDF-documenten](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Voorbeelden

Voeg een watermerk toe aan een bepaalde pagina van een pdf-document.

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

### Zie ook

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* naamruimte [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->