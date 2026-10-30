---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een afbeelding binnen een document voor."
type: docs
weight: 470
url: /nl/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

Stelt een afbeelding binnen een document voor.

```csharp
public abstract class WatermarkableImage : ContentPart
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Haalt de hoogte van deze [`WatermarkableImage`](../watermarkableimage) op in pixels. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Haalt de breedte van deze [`WatermarkableImage`](../watermarkableimage) op in pixels. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Voegt een watermerk toe aan deze [`WatermarkableImage`](../watermarkableimage). Deze methode gaat ervan uit dat de offset en grootte van het watermerk in pixels worden gemeten (indien ze zijn toegewezen). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Vindt alle afbeeldingen in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Vindt afbeeldingen volgens de opgegeven zoekcriteria. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Haalt de afbeelding op als byte-array. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Vindt alle mogelijke watermerken in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Opmerkingen

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### Voorbeelden

Voeg een watermerk toe aan alle afbeeldingen binnen een document van elk ondersteund type.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Initialiseer tekst- of afbeeldingwatermerk.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Zoek alle afbeeldingen in de inhoud.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Voeg watermerk toe.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // Sla wijzigingen op.
    watermarker.Save(@"D:\output.doc");
}
```

### Zie ook

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
