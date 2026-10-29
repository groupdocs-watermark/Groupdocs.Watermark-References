---
title: "GetImages"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Findet Bilder gemäß den angegebenen Suchkriterien."
type: docs
weight: 80
url: /de/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

Findet Bilder gemäß den angegebenen Suchkriterien.

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | Die zu verwendenden Suchkriterien. |

### Rückgabewert

Die Sammlung gefundener Bilder.

### Hinweise

Die Suche wird in den in [`SearchableObjects`](../searchableobjects) angegebenen Objekten durchgeführt.

Erfahren Sie mehr über das Suchen von Wasserzeichen [Suchen von Wasserzeichen](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Beispiele

Entferne alle Bilder, die dem Referenzbild ähneln, aus einem Dokument eines beliebigen unterstützten Typs.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Siehe auch

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

Findet alle Bilder im Dokument.

```csharp
public WatermarkableImageCollection GetImages()
```

### Rückgabewert

Die Sammlung gefundener Bilder.

### Hinweise

Die Suche wird in den in [`SearchableObjects`](../searchableobjects) angegebenen Objekten durchgeführt.

Erfahren Sie mehr über das Suchen von Wasserzeichen [Suchen von Wasserzeichen](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Beispiele

Füge allen Bildern in einem Dokument eines beliebigen unterstützten Typs ein Wasserzeichen hinzu.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Initialisiere Text- oder Bildwasserzeichen.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Finde alle Bilder im Dokument.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Wasserzeichen hinzufügen.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // Änderungen speichern.
    watermarker.Save(@"D:\output.doc");
}
```

### Siehe auch

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
