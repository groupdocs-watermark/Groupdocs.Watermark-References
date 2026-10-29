---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente une image à l'intérieur d'un document."
type: docs
weight: 470
url: /fr/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

Représente une image à l'intérieur d'un document.

```csharp
public abstract class WatermarkableImage : ContentPart
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Obtient la hauteur de ce [`WatermarkableImage`](../watermarkableimage) en pixels. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Obtient la largeur de ce [`WatermarkableImage`](../watermarkableimage) en pixels. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Ajoute un filigrane à ce [`WatermarkableImage`](../watermarkableimage). Cette méthode suppose que le décalage et la taille du filigrane sont mesurés en pixels (s'ils sont assignés). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trouve toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve les images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Obtient l'image sous forme de tableau d'octets. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trouve tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Remarques

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### Exemples

Ajoutez un filigrane à toutes les images d'un document de tout type pris en charge.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Initialisez le filigrane texte ou image.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Trouvez toutes les images dans le contenu.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Ajouter un filigrane.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // Enregistrez les modifications.
    watermarker.Save(@"D:\output.doc");
}
```

### Voir aussi

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
