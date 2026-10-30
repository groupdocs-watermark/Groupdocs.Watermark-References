---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ när vattenstämpeln läggs till som bakgrund på ett kalkylblad i ett Spreadsheet."
type: docs
weight: 2190
url: /sv/net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
---
## SpreadsheetBackgroundWatermarkOptions class

Representerar alternativ när vattenstämpeln läggs till som bakgrund på ett kalkylblad i ett Spreadsheet.

```csharp
public sealed class SpreadsheetBackgroundWatermarkOptions : WatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions](spreadsheetbackgroundwatermarkoptions)() | Initierar en ny instans av klassen [`SpreadsheetBackgroundWatermarkOptions`](../spreadsheetbackgroundwatermarkoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundHeight](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundheight) { get; set; } | Hämtar eller anger önskad höjd på bakgrundsbilden i pixlar. |
| [BackgroundWidth](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundwidth) { get; set; } | Hämtar eller anger önskad bredd på bakgrundsbilden i pixlar. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheetindex) { get; set; } | Hämtar eller anger indexet för kalkylbladet som vattenstämpeln ska läggas till i. |

### Anmärkningar

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Exempel

Lägg till textvattenstämpel på ett Excel‑kalkylblad som bakgrund.

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

### Se även

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
