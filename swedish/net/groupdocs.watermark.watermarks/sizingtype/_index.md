---
title: "SizingType"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Specificerar hur vattenstämpelns storlek ska beräknas."
type: docs
weight: 3300
url: /sv/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

Specificerar hur vattenstämpelns storlek ska beräknas.

```csharp
public enum SizingType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | Vattenstämpeln bör storleksanpassas automatiskt efter dess innehåll. |
| Absolute | `1` | Vattenstämpeln bör storleksanpassas till en exakt [`Width`](../../groupdocs.watermark/watermark/width) och [`Height`](../../groupdocs.watermark/watermark/height) |
| ScaleToParentDimensions | `2` | Vattenstämpeln bör skalas relativt till förälderns dimensioner med angiven [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor). |
| ScaleToParentArea | `3` | Vattenstämpeln bör skalas relativt till föräldraområdet med angiven [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) |

### Se även

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
