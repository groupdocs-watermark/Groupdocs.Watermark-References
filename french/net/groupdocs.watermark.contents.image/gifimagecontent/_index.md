---
title: "GifImageContent"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente une image gif où un filigrane peut être placé."
type: docs
weight: 390
url: /fr/net/groupdocs.watermark.contents.image/gifimagecontent/
---
## GifImageContent class

Représente une image gif où un filigrane peut être placé.

```csharp
public sealed class GifImageContent : MultiframeImageContent
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Frames](../../groupdocs.watermark.contents.image/multiframeimagecontent/frames) { get; } | Obtient la collection de tous les cadres de l'image. |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | Obtient la hauteur de ce [`ImageContent`](../imagecontent) en pixels. |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | Obtient la largeur de ce [`ImageContent`](../imagecontent) en pixels. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Libère l'instance actuelle. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trouve toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve les images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trouve tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Voir aussi

* class [MultiframeImageContent](../multiframeimagecontent)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
