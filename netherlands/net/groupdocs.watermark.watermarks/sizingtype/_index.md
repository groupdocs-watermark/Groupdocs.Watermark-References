---
title: "SizingType"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Specificeert hoe de grootte van een watermerk berekend moet worden."
type: docs
weight: 3300
url: /nl/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

Specificeert hoe de grootte van een watermerk berekend moet worden.

```csharp
public enum SizingType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | Watermerk moet automatisch worden geschaald op basis van de inhoud. |
| Absolute | `1` | Watermerk moet worden geschaald naar een exacte [`Width`](../../groupdocs.watermark/watermark/width) en [`Height`](../../groupdocs.watermark/watermark/height). |
| ScaleToParentDimensions | `2` | Watermerk moet worden geschaald ten opzichte van de afmetingen van de bovenliggende container met behulp van de opgegeven [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor). |
| ScaleToParentArea | `3` | Watermerk moet worden geschaald ten opzichte van het bovenliggende gebied met behulp van de opgegeven [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor). |

### Zie ook

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
