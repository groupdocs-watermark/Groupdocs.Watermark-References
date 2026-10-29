---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les critères de recherche pour trouver des images dans un contenu."
type: docs
weight: 2650
url: /fr/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

Représente les critères de recherche pour trouver des images dans un contenu.

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | Initialise une nouvelle instance de la classe [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) avec un flux spécifié. |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | Initialise une nouvelle instance de la classe [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) avec un chemin de fichier spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Obtient ou définit la différence maximale autorisée entre les images. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Obtient ou définit la liste des numéros de page spécifiques |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | Obtient ou définit la taille de la vignette. |

## Méthodes

| Nom | Description |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Inverse ce [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique OR. |

### Remarques

Ce critère de recherche utilise une vignette d'image binarisée pour calculer la similarité d'images.

### Voir aussi

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
