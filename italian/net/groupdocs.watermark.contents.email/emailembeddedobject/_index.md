---
title: "EmailEmbeddedObject"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un oggetto incorporato nel corpo di un messaggio email."
type: docs
weight: 370
url: /it/net/groupdocs.watermark.contents.email/emailembeddedobject/
---
## EmailEmbeddedObject class

Rappresenta un oggetto incorporato nel corpo di un messaggio email.

```csharp
public class EmailEmbeddedObject : EmailAttachmentBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | Restituisce o imposta il contenuto del file allegato. |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | Ottiene l'ID del contenuto di questo [`EmailAttachmentBase`](../emailattachmentbase). |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | Ottiene il tipo di media di questo [`EmailAttachmentBase`](../emailattachmentbase). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Carica un contenuto dal file allegato. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Carica un contenuto dal file allegato con le opzioni di caricamento specificate. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Carica un contenuto dal file allegato con le opzioni di caricamento e le impostazioni specificate. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Restituisce le informazioni su un documento memorizzato nel file allegato. |

### Vedi anche

* class [EmailAttachmentBase](../emailattachmentbase)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
