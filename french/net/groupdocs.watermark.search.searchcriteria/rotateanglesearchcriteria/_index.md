---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les critères permettant le filtrage par angle de rotation du filigrane."
type: docs
weight: 2710
url: /fr/net/groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/
---
## RotateAngleSearchCriteria class

Représente les critères permettant le filtrage par angle de rotation du filigrane.

```csharp
public class RotateAngleSearchCriteria : SearchCriteria
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RotateAngleSearchCriteria](rotateanglesearchcriteria)(double, double) | Initialise une nouvelle instance de la classe [`RotateAngleSearchCriteria`](../rotateanglesearchcriteria) avec un angle de départ et un angle de fin. |

## Propriétés

| Nom | Description |
| --- | --- |
| [MaximumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/maximumangle) { get; } | Obtient l'angle final en degrés. |
| [MinimumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/minimumangle) { get; } | Obtient l'angle de départ en degrés. |

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

Trouver et supprimer les filigranes en utilisant le critère de recherche.

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
