---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Haalt op of stelt de inhoudsobjecten in die moeten worden opgenomen in een watermerkzoekopdracht."
type: docs
weight: 20
url: /nl/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

Haalt op of stelt de inhoudsobjecten in die moeten worden opgenomen in een watermerkzoekopdracht.

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

De objecten die moeten worden opgenomen in een watermerkzoekopdracht.

### Opmerkingen

Deze eigenschap specificeert ook inhoudsobjecten die worden gebruikt bij het zoeken naar afbeeldingen. Voor meer informatie zie de methoden [`Search`](../search) en [`GetImages`](../getimages).

Meer informatie over het zoeken naar watermerken: [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Voorbeelden

Verwijder alle XObjects en Artefacten uit een pdf-document.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // Geef aan dat alleen XObjects en Artefacten moeten worden doorzocht.
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // Verwijder alle gevonden objecten.
    watermarks.Clear();

    // Sla wijzigingen op.
    watermarker.Save();
}
```

### Zie ook

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
