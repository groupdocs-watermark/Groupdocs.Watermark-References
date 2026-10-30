---
title: "GetImages"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Vindt afbeeldingen volgens de opgegeven zoekcriteria."
type: docs
weight: 80
url: /nl/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

Vindt afbeeldingen volgens de opgegeven zoekcriteria.

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | De te gebruiken zoekcriteria. |

### Retourwaarde

De verzameling gevonden afbeeldingen.

### Opmerkingen

Het zoeken wordt uitgevoerd in objecten gespecificeerd in [`SearchableObjects`](../searchableobjects).

Meer informatie over het zoeken naar watermerken [Zoeken naar watermerken](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Voorbeelden

Verwijder alle afbeeldingen die vergelijkbaar zijn met de referentie uit een document van elk ondersteund type.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Zie ook

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

Vindt alle afbeeldingen in het document.

```csharp
public WatermarkableImageCollection GetImages()
```

### Retourwaarde

De verzameling gevonden afbeeldingen.

### Opmerkingen

Het zoeken wordt uitgevoerd in objecten gespecificeerd in [`SearchableObjects`](../searchableobjects).

Meer informatie over het zoeken naar watermerken [Zoeken naar watermerken](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Voorbeelden

Voeg een watermerk toe aan alle afbeeldingen in een document van elk ondersteund type.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Initialiseer tekst- of afbeeldingwatermerk.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Zoek alle afbeeldingen in het document.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Voeg watermerk toe.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // Sla wijzigingen op.
    watermarker.Save(@"D:\output.doc");
}
```

### Zie ook

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
