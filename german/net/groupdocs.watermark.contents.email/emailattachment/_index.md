---
title: "EmailAttachment"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine an eine E‑Mail‑Nachricht angehängte Datei dar."
type: docs
weight: 320
url: /de/net/groupdocs.watermark.contents.email/emailattachment/
---
## EmailAttachment class

Stellt eine an eine E‑Mail‑Nachricht angehängte Datei dar.

```csharp
public class EmailAttachment : EmailAttachmentBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | Liefert oder setzt den Inhalt der angehängten Datei. |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | Liest die Content-ID dieses [`EmailAttachmentBase`](../emailattachmentbase). |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | Liest den Medientyp dieses [`EmailAttachmentBase`](../emailattachmentbase). |
| [Name](../../groupdocs.watermark.contents.email/emailattachment/name) { get; set; } | Liest oder legt den Namen der angehängten Datei fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Lädt einen Inhalt aus der angehängten Datei. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen und Einstellungen. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Liefert die Informationen zu einem im Anhang gespeicherten Dokument. |

### Siehe auch

* class [EmailAttachmentBase](../emailattachmentbase)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
