---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una raccolta di intestazioni e piè di pagina in un documento Word."
type: docs
weight: 1370
url: /it/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/
---
## WordProcessingHeaderFooterCollection class

Rappresenta una raccolta di intestazioni e piè di pagina in un documento Word.

```csharp
public class WordProcessingHeaderFooterCollection : ReadOnlyListBase<WordProcessingHeaderFooter>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Ottiene il numero di elementi contenuti nella raccolta. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Ottiene un valore che indica se la raccolta è di sola lettura. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Ottiene l'elemento all'indice specificato nella raccolta. |
| [Item](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/item) { get; } | Ottiene l'intestazione o il piè di pagina del tipo specificato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(WordProcessingHeaderFooter) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(WordProcessingHeaderFooter) |  |
| [LinkToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/linktoprevious)(bool) | Collega o scollega tutte le intestazioni e i piè di pagina alle corrispondenti intestazioni e piè di pagina nella sezione precedente. |

### Osservazioni

Questa collezione contiene gli elementi di tipo [`WordProcessingHeaderFooter`](../wordprocessingheaderfooter).

### Vedi anche

* class [ReadOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/readonlylistbase-1)
* class [WordProcessingHeaderFooter](../wordprocessingheaderfooter)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
