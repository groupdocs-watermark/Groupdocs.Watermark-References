---
title: "PdfOperatorCollection"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una raccolta di operatori in un contenuto pdf."
type: docs
weight: 720
url: /it/net/groupdocs.watermark.contents.pdf/pdfoperatorcollection/
---
## PdfOperatorCollection class

Rappresenta una raccolta di operatori in un contenuto pdf.

```csharp
public class PdfOperatorCollection : RemoveOnlyListBase<PdfOperator>
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
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfOperator) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfOperator) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfOperator) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Osservazioni

Questa collezione contiene gli elementi di tipo [`PdfOperator`](../pdfoperator).

### Vedi anche

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfOperator](../pdfoperator)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
