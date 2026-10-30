---
title: "PdfSearchableObjects"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Specificerar flaggor som representerar pdf-innehållsobjekt som ska inkluderas i en vattenstämpelsökning."
type: docs
weight: 2530
url: /sv/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

Specificerar flaggor som representerar pdf-innehållsobjekt som ska inkluderas i en vattenstämpelsökning.

```csharp
[Flags]
public enum PdfSearchableObjects
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Anger inga sökobjekt. |
| XObjects | `1` | Sök i XObjects. |
| Artifacts | `2` | Sök i artefakter. |
| Annotations | `4` | Sök i kommentarer. |
| Text | `8` | Sök i innehållstext. |
| Hyperlinks | `10` | Sök i hyperlänkar. |
| AttachedImages | `20` | Sök i bifogade bilder. |
| Vector | `40` | Sök bland operatörer. |
| All | `7F` | Sök i alla innehållsobjekt. |

### Se även

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
