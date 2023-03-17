---
title: EmailEmbeddedObject
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt een object dat is ingesloten in de hoofdtekst van een emailbericht.
type: docs
weight: 340
url: /nl/net/groupdocs.watermark.contents.email/emailembeddedobject/
---
## EmailEmbeddedObject class

Vertegenwoordigt een object dat is ingesloten in de hoofdtekst van een e-mailbericht.

```csharp
public class EmailEmbeddedObject : EmailAttachmentBase
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | Haalt de inhoud van het bijgevoegde bestand op of stelt deze in. |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | Krijgt de inhoud-ID hiervan[`EmailAttachmentBase`](../emailattachmentbase) . |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | Krijgt het mediatype hiervan[`EmailAttachmentBase`](../emailattachmentbase) . |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Laadt inhoud uit het bijgevoegde bestand. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Laadt inhoud uit het bijgevoegde bestand met de opgegeven laadopties. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Laadt inhoud uit het bijgevoegde bestand met de opgegeven laadopties en instellingen. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Haalt de informatie op over een document dat is opgeslagen in het bijgevoegde bestand. |

### Zie ook

* class [EmailAttachmentBase](../emailattachmentbase)
* naamruimte [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->