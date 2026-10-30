---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni quando si aggiunge una filigrana word art moderna a un foglio di lavoro Spreadsheet."
type: docs
weight: 2280
url: /it/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
---
## SpreadsheetWatermarkModernWordArtOptions class

Rappresenta le opzioni quando si aggiunge una filigrana word art moderna a un foglio di lavoro Spreadsheet.

```csharp
public sealed class SpreadsheetWatermarkModernWordArtOptions : SpreadsheetWatermarkBaseOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SpreadsheetWatermarkModernWordArtOptions](spreadsheetwatermarkmodernwordartoptions)() | Inizializza una nuova istanza della classe [`SpreadsheetWatermarkModernWordArtOptions`](../spreadsheetwatermarkmodernwordartoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | Ottiene o imposta il testo descrittivo (alternativo) che sarà associato a una forma. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Ottiene o imposta un valore che indica se la modifica della forma in Excel è vietata. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | Ottiene o imposta il nome di una forma. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheetindex) { get; set; } | Ottiene o imposta l'indice del foglio di lavoro a cui aggiungere il watermark. |

### Osservazioni

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Esempi

Aggiungi un watermark WordArt moderno a un documento Excel.

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

### Vedi anche

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
