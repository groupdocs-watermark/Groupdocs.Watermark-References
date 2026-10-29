---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente des critères permettant de filtrer par texte du filigrane."
type: docs
weight: 2750
url: /fr/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

Représente des critères permettant de filtrer par texte du filigrane.

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | Initialise une nouvelle instance de la classe [`TextSearchCriteria`](../textsearchcriteria) avec une expression régulière spécifiée. |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | Initialise une nouvelle instance de la classe [`TextSearchCriteria`](../textsearchcriteria) avec une chaîne de recherche. |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | Initialise une nouvelle instance de la classe [`TextSearchCriteria`](../textsearchcriteria) avec une chaîne de recherche et un indicateur de comparaison. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Obtient ou définit la liste des numéros de page spécifiques |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | Obtient le modèle de recherche. |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | Obtient ou définit une valeur indiquant que les caractères illisibles seront ignorés lors de la comparaison de chaînes. |

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

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
