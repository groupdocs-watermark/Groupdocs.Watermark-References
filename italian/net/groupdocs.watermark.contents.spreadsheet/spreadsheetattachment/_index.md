---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un file allegato a un documento Excel."
type: docs
weight: 1100
url: /it/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

Rappresenta un file allegato a un documento Excel.

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | Ottiene o imposta il testo descrittivo (alternativo) associato al file allegato. |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | Restituisce o imposta il contenuto del file allegato. |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | Ottiene o imposta l'altezza del riquadro dell'allegato in punti. |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | Ottiene un valore che indica se il contenuto contiene solo un collegamento al file. |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | Ottiene o imposta l'immagine di anteprima del file allegato come array di byte. |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | Ottiene il nome completo del file allegato. |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | Ottiene o imposta la larghezza del riquadro dell'allegato in punti. |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | Ottiene o imposta lo spostamento orizzontale del riquadro dell'allegato dal bordo sinistro del foglio di lavoro in punti. |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | Ottiene o imposta lo spostamento verticale del riquadro dell'allegato dal bordo superiore del foglio di lavoro in punti. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Carica un contenuto dal file allegato. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Carica un contenuto dal file allegato con le opzioni di caricamento specificate. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Carica un contenuto dal file allegato con le opzioni di caricamento e le impostazioni specificate. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Restituisce le informazioni su un documento memorizzato nel file allegato. |

### Vedi anche

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
