---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen dar, wenn das Wasserzeichen zu einer Spreadsheet‑Kopf‑/Fußzeile hinzugefügt wird."
type: docs
weight: 2270
url: /de/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
---
## SpreadsheetWatermarkHeaderFooterOptions class

Stellt Optionen dar, wenn das Wasserzeichen zu einer Spreadsheet‑Kopf‑/Fußzeile hinzugefügt wird.

```csharp
public sealed class SpreadsheetWatermarkHeaderFooterOptions : WatermarkOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SpreadsheetWatermarkHeaderFooterOptions](spreadsheetwatermarkheaderfooteroptions)() | Initialisiert eine neue Instanz der [`SpreadsheetWatermarkHeaderFooterOptions`](../spreadsheetwatermarkheaderfooteroptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheetindex) { get; set; } | Liest oder setzt den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt werden soll. |

### Hinweise

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Beispiele

Fügt ein Textwasserzeichen in die Kopfzeile des Excel-Arbeitsblatts ein.

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

### Siehe auch

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
