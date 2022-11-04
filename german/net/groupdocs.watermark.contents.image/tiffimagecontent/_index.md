---
title: TiffImageContent
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Stellt ein TIFFBild dar in dem ein Wasserzeichen platziert werden kann.
type: docs
weight: 410
url: /de/net/groupdocs.watermark.contents.image/tiffimagecontent/
---
## TiffImageContent class

Stellt ein TIFF-Bild dar, in dem ein Wasserzeichen platziert werden kann.

```csharp
public class TiffImageContent : MultiframeImageContent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Frames](../../groupdocs.watermark.contents.image/multiframeimagecontent/frames) { get; } | Ruft die Sammlung aller Frames des Bildes ab. |
| [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | Ruft die Höhe davon ab[`ImageContent`](../imagecontent) in Pixel. |
| [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | Ruft die Breite davon ab[`ImageContent`](../imagecontent) in Pixel. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Verwirft die aktuelle Instanz. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den angegebenen Objekten durchgeführt[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder nach den angegebenen Suchkriterien. Die Suche wird in den angegebenen Objekten durchgeführt[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in angegebenen Objekten durchgeführt[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen nach vorgegebenen Suchkriterien. Die Suche wird in den in angegebenen Objekten durchgeführt[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Siehe auch

* class [MultiframeImageContent](../multiframeimagecontent)
* namensraum [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->