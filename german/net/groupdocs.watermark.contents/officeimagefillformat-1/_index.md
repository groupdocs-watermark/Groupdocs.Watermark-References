---
title: "OfficeImageFillFormatTWatermarkableImage"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt die Einstellungen des Bildfüllformats in beliebigem unterstütztem Office-Inhalt dar."
type: docs
weight: 520
url: /de/net/groupdocs.watermark.contents/officeimagefillformat-1/
---
## OfficeImageFillFormat&lt;TWatermarkableImage&gt; class

Stellt die Einstellungen des Bildfüllformats in beliebigem unterstütztem Office-Inhalt dar.

```csharp
public abstract class OfficeImageFillFormat<TWatermarkableImage>
    where TWatermarkableImage : WatermarkableImage
```

| Parameter | Beschreibung |
| --- | --- |
| TWatermarkableImage | Der genaue Typ des wasserzeichnungsfähigen Bildes, das als Hintergrund verwendet wird. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [BackgroundImage](../../groupdocs.watermark.contents/officeimagefillformat-1/backgroundimage) { get; set; } | Liest oder setzt das Hintergrundbild. |
| abstract [TileAsTexture](../../groupdocs.watermark.contents/officeimagefillformat-1/tileastexture) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt wird. |
| abstract [Transparency](../../groupdocs.watermark.contents/officeimagefillformat-1/transparency) { get; set; } | Liest oder setzt die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 (vollständig transparent). |

### Siehe auch

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
