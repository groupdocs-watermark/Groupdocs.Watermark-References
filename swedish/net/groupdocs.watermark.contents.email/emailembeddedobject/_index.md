---
title: "EmailEmbeddedObject"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar ett objekt som är inbäddat i ett e‑postmeddelandes kropp."
type: docs
weight: 370
url: /sv/net/groupdocs.watermark.contents.email/emailembeddedobject/
---
## EmailEmbeddedObject class

Representerar ett objekt som är inbäddat i ett e‑postmeddelandes kropp.

```csharp
public class EmailEmbeddedObject : EmailAttachmentBase
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | Hämtar eller anger innehållet i den bifogade filen. |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | Hämtar innehålls‑id för detta [`EmailAttachmentBase`](../emailattachmentbase). |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | Hämtar mediatypen för detta [`EmailAttachmentBase`](../emailattachmentbase). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Läser in ett innehåll från den bifogade filen. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Läser in ett innehåll från den bifogade filen med de angivna inläsningsalternativen. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Läser in ett innehåll från den bifogade filen med de angivna inläsningsalternativen och inställningarna. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Hämtar information om ett dokument som lagras i den bifogade filen. |

### Se även

* class [EmailAttachmentBase](../emailattachmentbase)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
