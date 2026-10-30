---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una raccolta di allegati in un documento Excel."
type: docs
weight: 1110
url: /it/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/
---
## SpreadsheetAttachmentCollection class

Rappresenta una raccolta di allegati in un documento Excel.

```csharp
public class SpreadsheetAttachmentCollection : RemoveOnlyListBase<SpreadsheetAttachment>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Ottiene il numero di elementi contenuti nella raccolta. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Ottiene un valore che indica se la raccolta è di sola lettura. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Ottiene l'elemento all'indice specificato nella raccolta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddAttachment](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment)(byte[], string, byte[], double, double, double, double) | Aggiunge un allegato al [`SpreadsheetWorksheet`](../spreadsheetworksheet). |
| [AddLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink)(string, byte[], double, double, double, double) | Aggiunge un allegato tramite un collegamento (il documento non conterrà il contenuto del file allegato). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(SpreadsheetAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(SpreadsheetAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(SpreadsheetAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Osservazioni

Questa raccolta contiene gli elementi di tipo [`SpreadsheetAttachment`](../spreadsheetattachment).

### Vedi anche

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [SpreadsheetAttachment](../spreadsheetattachment)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
