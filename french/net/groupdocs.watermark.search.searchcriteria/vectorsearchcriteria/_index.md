---
title: "VectorSearchCriteria"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente des critères permettant de filtrer par couleur du filigrane."
type: docs
weight: 2760
url: /fr/net/groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/
---
## VectorSearchCriteria class

Représente des critères permettant de filtrer par couleur du filigrane.

```csharp
public class VectorSearchCriteria : SearchCriteria
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VectorSearchCriteria](vectorsearchcriteria)() | Initialise une nouvelle instance de la classe [`VectorSearchCriteria`](../vectorsearchcriteria). |

## Propriétés

| Nom | Description |
| --- | --- |
| [VectorColorRange](../../groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/vectorcolorrange) { get; set; } | Obtient ou définit la plage de couleurs utilisée pour filtrer les filigranes vectoriels par couleur de premier plan. |

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
using (Watermarker watermarker = new Watermarker(@"C:\test.pdf"))
{
    VectorSearchCriteria searchCriteria = new VectorSearchCriteria();
    Color watermarkColor = ColorTranslator.FromHtml("#a9aaae");
    GroupDocs.Watermark.Watermarks.Color fromSystemColor = GroupDocs.Watermark.Watermarks.Color.FromArgb(watermarkColor.A, watermarkColor.R, watermarkColor.G, watermarkColor.B);
    ColorRange criteriaVectorColorRange = new ColorRange(fromSystemColor)
    {
       MinBrightness = 0.1f,
       MaxBrightness = 0.7f
    };
    searchCriteria.VectorColorRange = criteriaVectorColorRange;
    PossibleWatermarkCollection possibleWatermarkCollection = watermarker.Search(searchCriteria);
    possibleWatermarkCollection.Clear();
    watermarker.Save(@"C:\modified_test.pdf");
}
```

### Voir aussi

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
