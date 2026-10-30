---
title: "EmailContent"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar ett e‑postmeddelande."
type: docs
weight: 360
url: /sv/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

Representerar ett e‑postmeddelande.

```csharp
public sealed class EmailContent : Content
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | Hämtar samlingen av alla bilagor i e‑postmeddelandet. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | Hämtar samlingen av BCC‑mottagare (blind carbon copy) i e‑postmeddelandet. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | Hämtar eller anger den rena textrepresentationen av meddelandetexten. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | Hämtar typen av e‑postmeddelandets kropp. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | Hämtar samlingen av CC‑mottagare (carbon copy) i e‑postmeddelandet. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | Hämtar samlingen av alla inbäddade objekt i e‑postmeddelandet. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | Hämtar avsändaradressen för e‑postmeddelandet. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | Hämtar eller anger HTML‑representationen av meddelandetexten. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | Hämtar eller anger ämnet för e‑postmeddelandet. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | Hämtar samlingen av mottagare för e‑postmeddelandet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Avslutar den aktuella instansen. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Anmärkningar

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### Se även

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
