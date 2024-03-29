---
title: SpreadsheetWatermarkHeaderFooterOptions
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt opties bij het toevoegen van het watermerk aan een spreadsheetkoptekst/voettekst.
type: docs
weight: 2200
url: /nl/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
---
## SpreadsheetWatermarkHeaderFooterOptions class

Vertegenwoordigt opties bij het toevoegen van het watermerk aan een spreadsheet-koptekst/voettekst.

```csharp
public sealed class SpreadsheetWatermarkHeaderFooterOptions : SpreadsheetWatermarkOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetWatermarkHeaderFooterOptions](spreadsheetwatermarkheaderfooteroptions)() | Initialiseert een nieuw exemplaar van het[`SpreadsheetWatermarkHeaderFooterOptions`](../spreadsheetwatermarkheaderfooteroptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheetindex) { get; set; } | Haalt of stelt de index van het werkblad in om het watermerk aan toe te voegen. |

### Opmerkingen

**Kom meer te weten:**

* [Voeg watermerken toe aan spreadsheetdocumenten](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Voorbeelden

Voeg een tekstwatermerk toe aan de koptekst van het Excel-werkblad.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));

    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
    options.WorksheetIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Zie ook

* class [SpreadsheetWatermarkOptions](../spreadsheetwatermarkoptions)
* naamruimte [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
