---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt opties voor wanneer het watermerk wordt toegevoegd als achtergrond aan een Spreadsheet-werkblad voor."
type: docs
weight: 2190
url: /nl/net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
---
## SpreadsheetBackgroundWatermarkOptions class

Stelt opties voor wanneer het watermerk wordt toegevoegd als achtergrond aan een Spreadsheet-werkblad voor.

```csharp
public sealed class SpreadsheetBackgroundWatermarkOptions : WatermarkOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions](spreadsheetbackgroundwatermarkoptions)() | Initialiseert een nieuw exemplaar van de [`SpreadsheetBackgroundWatermarkOptions`](../spreadsheetbackgroundwatermarkoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundHeight](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundheight) { get; set; } | Haalt of stelt de gewenste hoogte van de achtergrondafbeelding in pixels in. |
| [BackgroundWidth](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundwidth) { get; set; } | Haalt of stelt de gewenste breedte van de achtergrondafbeelding in pixels in. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheetindex) { get; set; } | Haalt of stelt de index van het werkblad in waarop het watermerk moet worden toegevoegd. |

### Opmerkingen

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Voorbeelden

Voeg een tekstwatermerk toe aan een werkblad van een Excel-document als achtergrond.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xlsx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
    options.WorksheetIndex = -1; // default
    options.BackgroundWidth = 800;
    options.BackgroundHeight = 600;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Zie ook

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
