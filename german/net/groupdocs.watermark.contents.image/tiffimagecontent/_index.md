---
title: "TiffImageContent"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein TIFF-Bild dar, in das ein Wasserzeichen eingefügt werden kann."
type: docs
weight: 460
url: /de/net/groupdocs.watermark.contents.image/tiffimagecontent/
---
## TiffImageContent class

Stellt ein TIFF-Bild dar, in das ein Wasserzeichen eingefügt werden kann.

```csharp
public class TiffImageContent : MultiframeImageContent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Frames](../../groupdocs.watermark.contents.image/multiframeimagecontent/frames) { get; } | Ermittelt die Sammlung aller Frames des Bildes. |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | Ermittelt die Höhe dieses [`ImageContent`](../imagecontent) in Pixeln. |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | Ermittelt die Breite dieses [`ImageContent`](../imagecontent) in Pixeln. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Gibt die aktuelle Instanz frei. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |

### Siehe auch

* class [MultiframeImageContent](../multiframeimagecontent)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
