---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Biedt opties om vereisten en streamdelegates in te stellen voor het genereren van een voorbeeld van een WordProcessing-document."
type: docs
weight: 2360
url: /nl/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions class

Biedt opties om vereisten en streamdelegates in te stellen voor het genereren van een voorbeeld van een WordProcessing-document.

```csharp
public class WordProcessingPreviewOptions : PreviewOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingPreviewOptions](wordprocessingpreviewoptions#constructor)(CreatePageStream) | Initialiseert een nieuw exemplaar van de [`WordProcessingPreviewOptions`](../wordprocessingpreviewoptions) klasse waardoor de uitvoerstroom wordt gesloten. |
| [WordProcessingPreviewOptions](wordprocessingpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialiseert een nieuw exemplaar van de [`WordProcessingPreviewOptions`](../wordprocessingpreviewoptions) klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Haalt op of stelt een exemplaar in van de delegate voor het maken van paginastromen. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Haalt op of stelt de hoogte van de paginavoorvertoning in. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Haalt op of stelt een array van paginanummers in om voorvertoningen te genereren. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Haalt of stelt het preview-afbeeldingsformaat in. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Haalt of stelt een instantie van de page preview completion delegate in. |
| [Resolution](../../groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/resolution) { get; set; } | Haalt of stelt de resolutie voor de gegenereerde afbeeldingen in, in dots per inch. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Haalt of stelt de breedte van de paginavoorvertoning in. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/defaultresolution) | Standaardresolutie in dots per inch. |

### Zie ook

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
