---
title: "EmailContent"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine E‑Mail‑Nachricht dar."
type: docs
weight: 360
url: /de/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

Stellt eine E‑Mail‑Nachricht dar.

```csharp
public sealed class EmailContent : Content
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | Liest die Sammlung aller Anhänge der E‑Mail‑Nachricht. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | Liest die Sammlung der BCC‑Empfänger (Blind Carbon Copy) der E‑Mail‑Nachricht. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | Liest oder setzt die Nur-Text-Darstellung des Nachrichtenkörpers. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | Liest den Typ des Nachrichtenkörpers der E‑Mail. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | Liest die Sammlung der CC‑Empfänger (Carbon Copy) der E‑Mail‑Nachricht. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | Liest die Sammlung aller eingebetteten Objekte der E‑Mail‑Nachricht. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | Liest die Absenderadresse der E‑Mail‑Nachricht. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | Liest oder setzt die HTML‑Darstellung des Nachrichtenkörpers. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | Liest oder setzt den Betreff der E‑Mail‑Nachricht. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | Liest die Sammlung der Empfänger der E‑Mail‑Nachricht. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Gibt die aktuelle Instanz frei. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |

### Hinweise

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### Siehe auch

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
