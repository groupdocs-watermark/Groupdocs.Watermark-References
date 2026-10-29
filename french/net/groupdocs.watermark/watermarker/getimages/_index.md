---
title: "GetImages"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Trouve les images selon les critères de recherche spécifiés."
type: docs
weight: 80
url: /fr/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

Trouve les images selon les critères de recherche spécifiés.

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | Les critères de recherche à utiliser. |

### Valeur de retour

La collection des images trouvées.

### Remarques

La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../searchableobjects).

En savoir plus sur la recherche de filigranes [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Exemples

Supprimer toutes les images similaires à la référence d'un document de tout type pris en charge.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Voir aussi

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

Trouve toutes les images dans le document.

```csharp
public WatermarkableImageCollection GetImages()
```

### Valeur de retour

La collection des images trouvées.

### Remarques

La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../searchableobjects).

En savoir plus sur la recherche de filigranes [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Exemples

Ajouter un filigrane à toutes les images d'un document de tout type pris en charge.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Initialisez le filigrane texte ou image.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Trouver toutes les images dans le document.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Ajouter un filigrane.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // Enregistrez les modifications.
    watermarker.Save(@"D:\output.doc");
}
```

### Voir aussi

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
