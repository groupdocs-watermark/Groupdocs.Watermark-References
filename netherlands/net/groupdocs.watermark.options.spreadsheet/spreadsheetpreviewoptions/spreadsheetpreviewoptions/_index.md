---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Initialiseert een nieuw exemplaar van de SpreadsheetPreviewOptionsgroupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions klasse waardoor de uitvoerstroom wordt gesloten."
type: docs
weight: 10
url: /nl/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions(CreatePageStream) {#constructor}

Initialiseert een nieuw exemplaar van de [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) klasse waardoor de uitvoerstroom wordt gesloten.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Maakt een stroom voor een specifieke paginavoorvertoning. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

---

## SpreadsheetPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialiseert een nieuw exemplaar van [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Maakt een stroom voor een specifieke paginavoorvertoning. |
| releasePageStream | ReleasePageStream | Geeft aan dat de generatie van de paginavoorvertoning is voltooid en haalt de uitvoerstroom op. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
