---
title: "EmailContent"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een e-mailbericht voor."
type: docs
weight: 360
url: /nl/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

Stelt een e-mailbericht voor.

```csharp
public sealed class EmailContent : Content
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | Haalt de collectie van alle bijlagen van het e-mailbericht op. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | Haalt de collectie van BCC (blind carbon copy) ontvangers van het e-mailbericht op. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | Haalt op of stelt de platte-tekstrepresentatie van de berichtinhoud in. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | Haalt het type van de e-mailberichtinhoud op. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | Haalt de collectie van CC (carbon copy) ontvangers van het e-mailbericht op. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | Haalt de collectie van alle ingebedde objecten van het e-mailbericht op. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | Haalt het afzenderadres van het e-mailbericht op. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | Haalt op of stelt de HTML-representatie van de berichtinhoud in. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | Haalt op of stelt het onderwerp van het e-mailbericht in. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | Haalt de collectie van ontvangers van het e-mailbericht op |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Verwijdert de huidige instantie. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Vindt alle afbeeldingen in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Vindt afbeeldingen volgens de opgegeven zoekcriteria. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Vindt alle mogelijke watermerken in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Opmerkingen

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### Zie ook

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
