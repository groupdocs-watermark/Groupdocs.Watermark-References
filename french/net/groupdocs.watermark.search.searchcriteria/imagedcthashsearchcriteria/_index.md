---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente un critère de recherche pour trouver des images dans un document."
type: docs
weight: 2630
url: /fr/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

Représente un critère de recherche pour trouver des images dans un document.

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | Initialise une nouvelle instance de la classe [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) avec un flux spécifié. |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | Initialise une nouvelle instance de la classe [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) avec un chemin de fichier spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Obtient ou définit la différence maximale autorisée entre les images. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Obtient ou définit la liste des numéros de page spécifiques |

## Méthodes

| Nom | Description |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Inverse ce [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique OR. |

### Remarques

Ce critère de recherche utilise un hachage d'image perceptuel basé sur la DCT pour calculer la similarité d'images. **En savoir plus :**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Exemples

Rechercher des images dans les fichiers joints (pdf).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // Spécifiez l'image d'échantillon pour comparer les images du document.
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // Rechercher des images similaires
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // Supprimer ou modifier les filigranes d'image trouvés
    // ...
}
```

### Voir aussi

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
