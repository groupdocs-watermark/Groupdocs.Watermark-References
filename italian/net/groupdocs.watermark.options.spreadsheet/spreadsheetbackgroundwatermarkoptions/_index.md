---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni quando si aggiunge il watermark come sfondo a un foglio di lavoro Spreadsheet."
type: docs
weight: 2190
url: /it/net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
---
## SpreadsheetBackgroundWatermarkOptions class

Rappresenta le opzioni quando si aggiunge il watermark come sfondo a un foglio di lavoro Spreadsheet.

```csharp
public sealed class SpreadsheetBackgroundWatermarkOptions : WatermarkOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions](spreadsheetbackgroundwatermarkoptions)() | Inizializza una nuova istanza della classe [`SpreadsheetBackgroundWatermarkOptions`](../spreadsheetbackgroundwatermarkoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundHeight](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundheight) { get; set; } | Ottiene o imposta l'altezza desiderata dell'immagine di sfondo in pixel. |
| [BackgroundWidth](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundwidth) { get; set; } | Ottiene o imposta la larghezza desiderata dell'immagine di sfondo in pixel. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheetindex) { get; set; } | Ottiene o imposta l'indice del foglio di lavoro a cui aggiungere il watermark. |

### Osservazioni

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Esempi

Aggiungi un watermark di testo a un foglio di lavoro di un documento Excel come sfondo.

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

### Vedi anche

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
