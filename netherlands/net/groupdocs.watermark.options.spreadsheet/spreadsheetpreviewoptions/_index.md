---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Biedt opties om vereisten en streamdelegates in te stellen voor het genereren van een voorbeeld van een Spreadsheet-document."
type: docs
weight: 2220
url: /nl/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions class

Biedt opties om vereisten en streamdelegates in te stellen voor het genereren van een voorbeeld van een Spreadsheet-document.

```csharp
public class SpreadsheetPreviewOptions : PreviewOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetPreviewOptions](spreadsheetpreviewoptions#constructor)(CreatePageStream) | Initialiseert een nieuw exemplaar van de [`SpreadsheetPreviewOptions`](../spreadsheetpreviewoptions) klasse waardoor de uitvoerstroom wordt gesloten. |
| [SpreadsheetPreviewOptions](spreadsheetpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialiseert een nieuw exemplaar van de [`SpreadsheetPreviewOptions`](../spreadsheetpreviewoptions) klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Haalt op of stelt een exemplaar in van de delegate voor het maken van paginastromen. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Haalt op of stelt de hoogte van de paginavoorvertoning in. |
| [OnlyDataArea](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/onlydataarea) { get; set; } | Haalt of stelt de vlag in voor het weergeven van alleen het gegevensgebied zonder kopteksten, voetteksten, marges. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Haalt op of stelt een array van paginanummers in om voorvertoningen te genereren. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Haalt of stelt het preview-afbeeldingsformaat in. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Haalt of stelt een instantie van de page preview completion delegate in. |
| [Resolution](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/resolution) { get; set; } | Haalt of stelt de resolutie voor de gegenereerde afbeeldingen in, in dots per inch. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Haalt of stelt de breedte van de paginavoorvertoning in. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/defaultresolution) | Standaardresolutie in dots per inch. |

### Zie ook

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
