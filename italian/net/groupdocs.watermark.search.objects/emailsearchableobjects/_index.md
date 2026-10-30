---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Specifica i flag che rappresentano gli oggetti dei messaggi email da includere in una ricerca di filigrana."
type: docs
weight: 2520
url: /it/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

Specifica i flag che rappresentano gli oggetti dei messaggi email da includere in una ricerca di filigrana.

```csharp
[Flags]
public enum EmailSearchableObjects
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Specifica nessun oggetto di ricerca. |
| Subject | `1` | Cerca nell'oggetto del messaggio. |
| PlainTextBody | `2` | Cerca nel corpo del messaggio in testo semplice. |
| HtmlBody | `4` | Cerca nel corpo del messaggio HTML. |
| AttachedImages | `8` | Cerca nelle immagini allegate. |
| EmbeddedImages | `10` | Cerca nelle immagini incorporate. |
| All | `1F` | Cerca in tutti gli oggetti email. |

### Vedi anche

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
