---
title: SpreadsheetBackgroundWatermarkOptions
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt opties bij het toevoegen van het watermerk als achtergrond aan een Spreadsheetwerkblad.
type: docs
weight: 2120
url: /nl/net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
---
## SpreadsheetBackgroundWatermarkOptions class

Vertegenwoordigt opties bij het toevoegen van het watermerk als achtergrond aan een Spreadsheet-werkblad.

```csharp
public sealed class SpreadsheetBackgroundWatermarkOptions : SpreadsheetWatermarkOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions](spreadsheetbackgroundwatermarkoptions)() | Initialiseert een nieuw exemplaar van het[`SpreadsheetBackgroundWatermarkOptions`](../spreadsheetbackgroundwatermarkoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundHeight](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundheight) { get; set; } | Haalt of stelt de gewenste hoogte van de achtergrondafbeelding in pixels in. |
| [BackgroundWidth](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundwidth) { get; set; } | Haal de gewenste breedte van de achtergrondafbeelding in pixels op of stel deze in. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheetindex) { get; set; } | Haal de index van het werkblad op of stel deze in om het watermerk aan toe te voegen. |

### Opmerkingen

**Kom meer te weten:**

* [Voeg watermerken toe aan spreadsheetdocumenten](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Voorbeelden

Voeg tekstwatermerk toe aan een Excel-documentwerkblad als achtergrond.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xlsx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
    options.WorksheetIndex = -1; // standaard
    options.BackgroundWidth = 800;
    options.BackgroundHeight = 600;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Zie ook

* class [SpreadsheetWatermarkOptions](../spreadsheetwatermarkoptions)
* naamruimte [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
