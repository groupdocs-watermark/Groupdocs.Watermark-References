---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una raccolta di oggetti incorporati in un messaggio email."
type: docs
weight: 380
url: /it/net/groupdocs.watermark.contents.email/emailembeddedobjectcollection/
---
## EmailEmbeddedObjectCollection class

Rappresenta una raccolta di oggetti incorporati in un messaggio email.

```csharp
public class EmailEmbeddedObjectCollection : RemoveOnlyListBase<EmailEmbeddedObject>
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
| [Add](../../groupdocs.watermark.contents.email/emailembeddedobjectcollection/add)(byte[], string) | Aggiunge una risorsa incorporata a [`EmailContent`](../emailcontent). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailEmbeddedObject) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailEmbeddedObject) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailEmbeddedObject) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Osservazioni

Questa collezione contiene gli elementi di tipo [`EmailEmbeddedObject`](../emailembeddedobject).

### Vedi anche

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailEmbeddedObject](../emailembeddedobject)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
