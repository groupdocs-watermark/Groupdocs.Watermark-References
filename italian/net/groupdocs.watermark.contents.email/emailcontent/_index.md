---
title: "EmailContent"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un messaggio email."
type: docs
weight: 360
url: /it/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

Rappresenta un messaggio email.

```csharp
public sealed class EmailContent : Content
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | Ottiene la collezione di tutti gli allegati del messaggio email. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | Ottiene la collezione dei destinatari BCC (blind carbon copy) del messaggio email. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | Ottiene o imposta la rappresentazione in testo semplice del corpo del messaggio. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | Ottiene il tipo del corpo del messaggio email. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | Ottiene la collezione dei destinatari CC (carbon copy) del messaggio email. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | Ottiene la collezione di tutti gli oggetti incorporati del messaggio email. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | Ottiene l'indirizzo mittente del messaggio email. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | Ottiene o imposta la rappresentazione HTML del corpo del messaggio. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | Ottiene o imposta l'oggetto del messaggio email. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | Ottiene la collezione dei destinatari del messaggio email. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Elimina l'istanza corrente. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trova tutte le immagini nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trova le immagini secondo i criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trova tutte le possibili filigrane nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trova possibili filigrane in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Osservazioni

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### Vedi anche

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
