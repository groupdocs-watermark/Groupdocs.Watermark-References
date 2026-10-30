---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Geeft de opties weer bij het toevoegen van het watermerk aan een Spreadsheet-kop-/voettekst."
type: docs
weight: 2270
url: /nl/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
---
## SpreadsheetWatermarkHeaderFooterOptions class

Geeft de opties weer bij het toevoegen van het watermerk aan een Spreadsheet-kop-/voettekst.

```csharp
public sealed class SpreadsheetWatermarkHeaderFooterOptions : WatermarkOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetWatermarkHeaderFooterOptions](spreadsheetwatermarkheaderfooteroptions)() | Initialiseert een nieuw exemplaar van de [`SpreadsheetWatermarkHeaderFooterOptions`](../spreadsheetwatermarkheaderfooteroptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheetindex) { get; set; } | Haalt of stelt de index van het werkblad in waarop het watermerk moet worden toegevoegd. |

### Opmerkingen

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Voorbeelden

Voeg een tekstwatermerk toe aan de header van het Excel-werkblad.

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

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
