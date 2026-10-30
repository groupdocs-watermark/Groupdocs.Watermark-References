---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Specificerar flaggor som representerar e-postmeddelandeobjekt som ska inkluderas i en vattenstämpelsökning."
type: docs
weight: 2520
url: /sv/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

Specificerar flaggor som representerar e-postmeddelandeobjekt som ska inkluderas i en vattenstämpelsökning.

```csharp
[Flags]
public enum EmailSearchableObjects
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Anger inga sökobjekt. |
| Subject | `1` | Sök i meddelandets ämne. |
| PlainTextBody | `2` | Sök i meddelandets vanliga textinnehåll. |
| HtmlBody | `4` | Sök i meddelandets HTML-kropp. |
| AttachedImages | `8` | Sök i bifogade bilder. |
| EmbeddedImages | `10` | Sök i inbäddade bilder. |
| All | `1F` | Sök i alla e-postobjekt. |

### Se även

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
