---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Biedt opties om vereisten en stream-delegates in te stellen voor het genereren van een voorbeeld van een Presentatie-document."
type: docs
weight: 2030
url: /nl/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/
---
## PresentationPreviewOptions class

Biedt opties om vereisten en stream-delegates in te stellen voor het genereren van een voorbeeld van een Presentatie-document.

```csharp
public class PresentationPreviewOptions : PreviewOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor)(CreatePageStream) | Initialiseert een nieuw exemplaar van de [`PresentationPreviewOptions`](../presentationpreviewoptions) klasse waardoor de uitvoerstroom wordt gesloten. |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialiseert een nieuw exemplaar van de [`PresentationPreviewOptions`](../presentationpreviewoptions) klasse waardoor de uitvoerstroom wordt geretourneerd aan de client voor verder gebruik. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Haalt op of stelt een exemplaar in van de delegate voor het maken van paginastromen. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Haalt op of stelt de hoogte van de paginavoorvertoning in. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Haalt op of stelt een array van paginanummers in om voorvertoningen te genereren. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Haalt of stelt het preview-afbeeldingsformaat in. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Haalt of stelt een instantie van de page preview completion delegate in. |
| [Resolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/resolution) { get; set; } | Haalt of stelt de resolutie voor de gegenereerde afbeeldingen in, in dots per inch. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Haalt of stelt de breedte van de paginavoorvertoning in. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/defaultresolution) | Standaardresolutie in dots per inch. |

### Zie ook

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
