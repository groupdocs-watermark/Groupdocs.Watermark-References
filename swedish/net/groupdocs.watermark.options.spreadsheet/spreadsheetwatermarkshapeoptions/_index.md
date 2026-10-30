---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ när en formvattenstämpel läggs till i ett Spreadsheet‑arbetsblad."
type: docs
weight: 2290
url: /sv/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
---
## SpreadsheetWatermarkShapeOptions class

Representerar alternativ när en formvattenstämpel läggs till i ett Spreadsheet‑arbetsblad.

```csharp
public sealed class SpreadsheetWatermarkShapeOptions : SpreadsheetWatermarkBaseOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SpreadsheetWatermarkShapeOptions](spreadsheetwatermarkshapeoptions)() | Initierar en ny instans av klassen [`SpreadsheetWatermarkShapeOptions`](../spreadsheetwatermarkshapeoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | Hämtar eller anger den beskrivande (alternativa) texten som kommer att associeras med en form. |
| [Effects](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects) { get; set; } | Hämtar eller anger ett värde av [`SpreadsheetImageEffects`](../spreadsheetimageeffects) eller [`SpreadsheetTextEffects`](../spreadsheettexteffects) för effekter som ska tillämpas på vattenstämpeln. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Hämtar eller anger ett värde som indikerar om redigering av formen i Excel är förbjuden. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | Hämtar eller anger namnet på en form. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheetindex) { get; set; } | Hämtar eller anger indexet för kalkylbladet som vattenstämpeln ska läggas till i. |

### Anmärkningar

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Exempel

Lägg till vattenstämpel på ett specifikt kalkylblad i ett Excel-dokument.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
    options.WorksheetIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Se även

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
