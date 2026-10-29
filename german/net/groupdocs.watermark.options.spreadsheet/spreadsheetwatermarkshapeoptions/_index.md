---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen dar, wenn ein Form‑Wasserzeichen zu einem Spreadsheet‑Arbeitsblatt hinzugefügt wird."
type: docs
weight: 2290
url: /de/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
---
## SpreadsheetWatermarkShapeOptions class

Stellt Optionen dar, wenn ein Form‑Wasserzeichen zu einem Spreadsheet‑Arbeitsblatt hinzugefügt wird.

```csharp
public sealed class SpreadsheetWatermarkShapeOptions : SpreadsheetWatermarkBaseOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SpreadsheetWatermarkShapeOptions](spreadsheetwatermarkshapeoptions)() | Initialisiert eine neue Instanz der [`SpreadsheetWatermarkShapeOptions`](../spreadsheetwatermarkshapeoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | Liest oder setzt den beschreibenden (alternativen) Text, der mit einer Form verknüpft wird. |
| [Effects](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects) { get; set; } | Liest oder setzt einen Wert von [`SpreadsheetImageEffects`](../spreadsheetimageeffects) oder [`SpreadsheetTextEffects`](../spreadsheettexteffects) für Effekte, die auf das Wasserzeichen angewendet werden sollen. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob das Bearbeiten der Form in Excel verboten ist. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | Liest oder setzt den Namen einer Form. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheetindex) { get; set; } | Liest oder setzt den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt werden soll. |

### Hinweise

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Beispiele

Füge ein Wasserzeichen zu einem bestimmten Arbeitsblatt eines Excel-Dokuments hinzu.

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

### Siehe auch

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
