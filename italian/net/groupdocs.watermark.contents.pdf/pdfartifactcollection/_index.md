---
title: PdfArtifactCollection
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Rappresenta una raccolta di artefatti in un contenuto pdf.
type: docs
weight: 560
url: /it/net/groupdocs.watermark.contents.pdf/pdfartifactcollection/
---
## PdfArtifactCollection class

Rappresenta una raccolta di artefatti in un contenuto pdf.

```csharp
public class PdfArtifactCollection : RemoveOnlyListBase<PdfArtifact>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Ottiene il numero di elementi contenuti nella raccolta. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Ottiene un valore che indica se la raccolta è di sola lettura. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Ottiene l'elemento in corrispondenza dell'indice specificato nella raccolta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfArtifact) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfArtifact) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfArtifact) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Osservazioni

Questa raccolta contiene gli elementi di[`PdfArtifact`](../pdfartifact) tipo.

### Guarda anche

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfArtifact](../pdfartifact)
* spazio dei nomi [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->