---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni quando si aggiunge una filigrana a forma a un foglio di lavoro Spreadsheet."
type: docs
weight: 2290
url: /it/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
---
## SpreadsheetWatermarkShapeOptions class

Rappresenta le opzioni quando si aggiunge una filigrana a forma a un foglio di lavoro Spreadsheet.

```csharp
public sealed class SpreadsheetWatermarkShapeOptions : SpreadsheetWatermarkBaseOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SpreadsheetWatermarkShapeOptions](spreadsheetwatermarkshapeoptions)() | Inizializza una nuova istanza della classe [`SpreadsheetWatermarkShapeOptions`](../spreadsheetwatermarkshapeoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | Ottiene o imposta il testo descrittivo (alternativo) che sarà associato a una forma. |
| [Effects](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects) { get; set; } | Ottiene o imposta un valore di [`SpreadsheetImageEffects`](../spreadsheetimageeffects) o [`SpreadsheetTextEffects`](../spreadsheettexteffects) per gli effetti che dovrebbero essere applicati al watermark. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Ottiene o imposta un valore che indica se la modifica della forma in Excel è vietata. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | Ottiene o imposta il nome di una forma. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheetindex) { get; set; } | Ottiene o imposta l'indice del foglio di lavoro a cui aggiungere il watermark. |

### Osservazioni

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Esempi

Aggiungi il watermark a un foglio di lavoro specifico di un documento Excel.

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

### Vedi anche

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
