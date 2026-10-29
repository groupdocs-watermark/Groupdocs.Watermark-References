---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les critères de recherche pour trouver des images dans un contenu."
type: docs
weight: 2620
url: /fr/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

Représente les critères de recherche pour trouver des images dans un contenu.

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | Initialise une nouvelle instance de la classe [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) avec un flux spécifié. |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | Initialise une nouvelle instance de la classe [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) avec un chemin de fichier spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | Obtient ou définit le nombre de compartiments qui seront utilisés pour construire les histogrammes de couleur. |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Obtient ou définit la différence maximale autorisée entre les images. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Obtient ou définit la liste des numéros de page spécifiques |

## Méthodes

| Nom | Description |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Inverse ce [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique OR. |

### Remarques

Ce critère de recherche utilise des histogrammes de couleur d'image pour calculer la similarité d'image.

### Voir aussi

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
