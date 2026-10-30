---
title: "ReadOnlyListBaseT"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Fornisce la classe base astratta per un elenco readonly tipizzato in modo forte."
type: docs
weight: 110
url: /it/net/groupdocs.watermark.common/readonlylistbase-1/
---
## ReadOnlyListBase&lt;T&gt; class

Fornisce la classe base astratta per un elenco in sola lettura tipizzato fortemente.

```csharp
public abstract class ReadOnlyListBase<T> : IList, IList<T>
```

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'elemento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Ottiene il numero di elementi contenuti nella raccolta. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Ottiene un valore che indica se la raccolta è di sola lettura. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Ottiene l'elemento all'indice specificato nella raccolta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) | Determina se la raccolta contiene un elemento specifico. |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() | Restituisce un enumeratore che itera attraverso una raccolta. |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) | Determina l'indice di un elemento specifico nella raccolta. |

### Vedi anche

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
