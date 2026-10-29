---
title: "AttachmentWatermarkableImage"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein angehängtes Bild innerhalb eines Inhalts beliebigen unterstützten Typs dar."
type: docs
weight: 20
url: /de/net/groupdocs.watermark.common/attachmentwatermarkableimage/
---
## AttachmentWatermarkableImage class

Stellt ein angehängtes Bild innerhalb eines Inhalts beliebigen unterstützten Typs dar.

```csharp
public class AttachmentWatermarkableImage : WatermarkableImage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Liest die Höhe dieses [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in Pixeln. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Liest die Breite dieses [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in Pixeln. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Fügt diesem [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) ein Wasserzeichen hinzu. Diese Methode geht davon aus, dass Wasserzeichen‑Versatz und -Größe in Pixeln gemessen werden (falls sie zugewiesen wurden). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Liefert das Bild als Byte-Array. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |

### Siehe auch

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
