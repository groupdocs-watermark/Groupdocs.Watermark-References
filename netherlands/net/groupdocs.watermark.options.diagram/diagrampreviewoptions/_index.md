---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Biedt opties om vereisten en stream-delegates in te stellen voor het genereren van een voorbeeld van een Diagram-document."
type: docs
weight: 1730
url: /nl/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/
---
## DiagramPreviewOptions class

Biedt opties om vereisten en stream-delegates in te stellen voor het genereren van een voorbeeld van een Diagram-document.

```csharp
public class DiagramPreviewOptions : PreviewOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor)(CreatePageStream) | Initialiseert een nieuw exemplaar van de [`DiagramPreviewOptions`](../diagrampreviewoptions) klasse waardoor de uitvoerstroom wordt gesloten. |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialiseert een nieuw exemplaar van de [`DiagramPreviewOptions`](../diagrampreviewoptions) klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Haalt op of stelt een exemplaar in van de delegate voor het maken van paginastromen. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Haalt op of stelt de hoogte van de paginavoorvertoning in. |
| [HighQualityRendering](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/highqualityrendering) { get; set; } | Haalt een vlag op of stelt deze in voor weergave van hoge kwaliteit. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Haalt op of stelt een array van paginanummers in om voorvertoningen te genereren. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Haalt of stelt het preview-afbeeldingsformaat in. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Haalt of stelt een instantie van de page preview completion delegate in. |
| [Resolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/resolution) { get; set; } | Haalt of stelt de resolutie voor de gegenereerde afbeeldingen in, in dots per inch. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Haalt of stelt de breedte van de paginavoorvertoning in. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/defaultresolution) | Standaardresolutie in dots per inch. |

### Zie ook

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
