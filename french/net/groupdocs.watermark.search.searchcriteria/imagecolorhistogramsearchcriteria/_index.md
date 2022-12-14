---
title: ImageColorHistogramSearchCriteria
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente les critères de recherche pour trouver des images dans un contenu.
type: docs
weight: 2580
url: /fr/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

Représente les critères de recherche pour trouver des images dans un contenu.

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | Initialise une nouvelle instance du[`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) classe avec un flux spécifié. |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | Initialise une nouvelle instance du[`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) classe avec un chemin de fichier spécifié. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | Obtient ou définit un nombre de bacs qui seront utilisés pour créer des histogrammes de couleurs. |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Obtient ou définit la différence maximale autorisée entre les images. |

## Méthodes

| Nom | La description |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combine ceci[`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Annule cela[`SearchCriteria`](../searchcriteria) . |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combine ceci[`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique OR. |

### Remarques

Ce critère de recherche utilise des histogrammes de couleur d'image pour calculer la similarité de l'image.

### Voir également

* class [ImageSearchCriteria](../imagesearchcriteria)
* espace de noms [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
