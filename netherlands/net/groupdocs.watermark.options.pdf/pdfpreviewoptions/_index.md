---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Biedt opties om vereisten en stream‑delegaten in te stellen voor het genereren van een voorbeeld van een PDF‑document."
type: docs
weight: 1960
url: /nl/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/
---
## PdfPreviewOptions class

Biedt opties om vereisten en stream‑delegaten in te stellen voor het genereren van een voorbeeld van een PDF‑document.

```csharp
public class PdfPreviewOptions : PreviewOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfPreviewOptions](pdfpreviewoptions#constructor)(CreatePageStream) | Initialiseert een nieuw exemplaar van de [`PdfPreviewOptions`](../pdfpreviewoptions) klasse, waardoor de uitvoerstroom wordt gesloten. |
| [PdfPreviewOptions](pdfpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialiseert een nieuw exemplaar van de [`PdfPreviewOptions`](../pdfpreviewoptions) klasse, waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Haalt op of stelt een exemplaar in van de delegate voor het maken van paginastromen. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Haalt op of stelt de hoogte van de paginavoorvertoning in. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Haalt op of stelt een array van paginanummers in om voorvertoningen te genereren. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Haalt of stelt het preview-afbeeldingsformaat in. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Haalt of stelt een instantie van de page preview completion delegate in. |
| [Resolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/resolution) { get; set; } | Haalt of stelt de resolutie voor de gegenereerde afbeeldingen in, in dots per inch. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Haalt of stelt de breedte van de paginavoorvertoning in. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/defaultresolution) | Standaardresolutie in dots per inch. |

### Zie ook

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
