---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una raccolta di allegati in un messaggio email."
type: docs
weight: 340
url: /it/net/groupdocs.watermark.contents.email/emailattachmentcollection/
---
## EmailAttachmentCollection class

Rappresenta una raccolta di allegati in un messaggio email.

```csharp
public class EmailAttachmentCollection : RemoveOnlyListBase<EmailAttachment>
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
| [Add](../../groupdocs.watermark.contents.email/emailattachmentcollection/add)(byte[], string) | Aggiunge un allegato a [`EmailContent`](../emailcontent). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Osservazioni

Questa collezione contiene gli elementi di tipo [`EmailAttachment`](../emailattachment).

### Vedi anche

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailAttachment](../emailattachment)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
