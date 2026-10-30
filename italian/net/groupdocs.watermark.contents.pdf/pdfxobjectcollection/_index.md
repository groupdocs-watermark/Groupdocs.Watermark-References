---
title: "PdfXObjectCollection"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una raccolta di XObjects in un documento pdf."
type: docs
weight: 840
url: /it/net/groupdocs.watermark.contents.pdf/pdfxobjectcollection/
---
## PdfXObjectCollection class

Rappresenta una raccolta di XObjects in un documento pdf.

```csharp
public class PdfXObjectCollection : RemoveOnlyListBase<PdfXObject>
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
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfXObject) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfXObject) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfXObject) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Osservazioni

Questa raccolta contiene gli elementi di tipo [`PdfXObject`](../pdfxobject).

### Vedi anche

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfXObject](../pdfxobject)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
