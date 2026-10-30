---
title: "FromExtension"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Mappar filändelsen till filtypen."
type: docs
weight: 590
url: /sv/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

Mappar filändelsen till filtypen.

```csharp
public static FileType FromExtension(string extension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filändelse | Sträng | Filändelsen (inklusive punkten "."). |

### Returvärde

När filtypen stöds returneras den, annars returneras standard‑[`Unknown`](../unknown)‑filtypen.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *extension* är null eller en tom sträng. |

### Se även

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
