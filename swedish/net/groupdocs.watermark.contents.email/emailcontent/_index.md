---
title: EmailContent
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar ett epostmeddelande.
type: docs
weight: 330
url: /sv/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

Representerar ett e-postmeddelande.

```csharp
public sealed class EmailContent : Content
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | Hämtar samlingen av alla bilagor i e-postmeddelandet. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | Hämtar samlingen av BCC-mottagare (blind carbon copy) av e-postmeddelandet. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | Hämtar eller ställer in ren textrepresentation av meddelandetexten. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | Hämtar typen av e-postmeddelandetext. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | Hämtar samlingen av CC-mottagare (carbon copy) av e-postmeddelandet. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | Hämtar samlingen av alla inbäddade objekt i e-postmeddelandet. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | Hämtar från-adressen för e-postmeddelandet. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | Hämtar eller ställer in html-representationen av meddelandetexten. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | Hämtar eller ställer in ämnet för e-postmeddelandet. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | Hämtar samlingen av mottagare av e-postmeddelandet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Tar bort den aktuella instansen. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenstämplar enligt angivna sökkriterier. Sökningen utförs i de objekt som anges i[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Anmärkningar

**Läs mer:**

* [Lägg till vattenstämplar i e-postbilagor](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [E-postbilagor](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [E-postmeddelanden](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### Se även

* class [Content](../../groupdocs.watermark.contents/content)
* namnutrymme [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->