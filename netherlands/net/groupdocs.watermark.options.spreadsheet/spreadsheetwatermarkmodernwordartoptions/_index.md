---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Geeft de opties weer bij het toevoegen van een modern woordkunst-watermerk aan een Spreadsheet-werkblad."
type: docs
weight: 2280
url: /nl/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
---
## SpreadsheetWatermarkModernWordArtOptions class

Geeft de opties weer bij het toevoegen van een modern woordkunst-watermerk aan een Spreadsheet-werkblad.

```csharp
public sealed class SpreadsheetWatermarkModernWordArtOptions : SpreadsheetWatermarkBaseOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetWatermarkModernWordArtOptions](spreadsheetwatermarkmodernwordartoptions)() | Initialiseert een nieuw exemplaar van de [`SpreadsheetWatermarkModernWordArtOptions`](../spreadsheetwatermarkmodernwordartoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | Haalt of stelt de beschrijvende (alternatieve) tekst in die aan een vorm wordt gekoppeld. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Haalt of stelt een waarde in die aangeeft of bewerken van de vorm in Excel verboden is. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | Haalt of stelt de naam van een vorm in. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheetindex) { get; set; } | Haalt of stelt de index van het werkblad in waarop het watermerk moet worden toegevoegd. |

### Opmerkingen

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Voorbeelden

Voeg een modern WordArt-watermerk toe aan een Excel-document.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
    options.WorksheetIndex = -1; // default
    options.IsLocked = false; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Zie ook

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
