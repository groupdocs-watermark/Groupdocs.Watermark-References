---
title: "RemoveOnlyListBaseT"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Fornisce la classe base astratta per un elenco removeonly tipizzato in modo forte."
type: docs
weight: 130
url: /it/net/groupdocs.watermark.common/removeonlylistbase-1/
---
## RemoveOnlyListBase&lt;T&gt; class

Fornisce la classe base astratta per un elenco di rimozione sola tipizzato fortemente.

```csharp
public abstract class RemoveOnlyListBase<T> : ReadOnlyListBase<T>
```

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'elemento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Ottiene il numero di elementi contenuti nella raccolta. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Ottiene un valore che indica se la raccolta è di sola lettura. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Ottiene l'elemento all'indice specificato nella raccolta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() | Rimuove tutti gli elementi dalla raccolta. |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(T) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) | Rimuove l'elemento all'indice specificato. |

### Vedi anche

* class [ReadOnlyListBase&lt;T&gt;](../readonlylistbase-1)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
