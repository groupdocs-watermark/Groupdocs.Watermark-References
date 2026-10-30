---
title: "SizingType"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Specifica come deve essere calcolata la dimensione della filigrana."
type: docs
weight: 3300
url: /it/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

Specifica come deve essere calcolata la dimensione della filigrana.

```csharp
public enum SizingType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | La filigrana dovrebbe essere dimensionata automaticamente in base al suo contenuto. |
| Absolute | `1` | La filigrana dovrebbe essere dimensionata a una esatta [`Width`](../../groupdocs.watermark/watermark/width) e [`Height`](../../groupdocs.watermark/watermark/height) |
| ScaleToParentDimensions | `2` | La filigrana dovrebbe essere scalata rispetto alle dimensioni del genitore utilizzando il [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) specificato. |
| ScaleToParentArea | `3` | La filigrana dovrebbe essere scalata rispetto all'area del genitore utilizzando il [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) specificato |

### Vedi anche

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
