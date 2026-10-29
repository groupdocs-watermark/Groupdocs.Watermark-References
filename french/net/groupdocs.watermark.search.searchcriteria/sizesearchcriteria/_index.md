---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente des critères permettant de filtrer par taille de filigrane."
type: docs
weight: 2730
url: /fr/net/groupdocs.watermark.search.searchcriteria/sizesearchcriteria/
---
## SizeSearchCriteria class

Représente des critères permettant de filtrer par taille de filigrane.

```csharp
public class SizeSearchCriteria : SearchCriteria
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SizeSearchCriteria](sizesearchcriteria)(Dimension, double, double) | Initialise une nouvelle instance de la classe [`SizeSearchCriteria`](../sizesearchcriteria) avec une dimension spécifiée, une valeur de départ et une valeur de fin. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Dimension](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/dimension) { get; } | Obtient la dimension du filigrane à rechercher. |
| [Maximum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/maximum) { get; } | Obtient la valeur de fin. |
| [Minimum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/minimum) { get; } | Obtient la valeur de départ. |

## Méthodes

| Nom | Description |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Inverse ce [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique OR. |

### Remarques

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Exemples

Trouve et supprime le filigrane en utilisant les critères de recherche.

```csharp
using (Watermarker watermarker = new Watermarker(@"C:\test.some_ext"))
{
    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
    TextSearchCriteria textCriteria = new TextSearchCriteria(new Regex("^Test watermark$"));
    PossibleWatermarkCollection watermarks = watermarker.Search(textCriteria.And(widthRange.Or(rotateAngle)));
    watermarks.Clear();
    watermarker.Save();
}
```

### Voir aussi

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
