---
title: "PdfTextFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente une collection de fragments de texte formaté dans le texte principal d'un contenu pdf."
type: docs
weight: 790
url: /fr/net/groupdocs.watermark.contents.pdf/pdftextformattedtextfragmentcollection/
---
## PdfTextFormattedTextFragmentCollection class

Représente une collection de fragments de texte formaté dans le texte principal d'un contenu pdf.

```csharp
public class PdfTextFormattedTextFragmentCollection : PdfFormattedTextFragmentCollection
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CollectionType](../../groupdocs.watermark.search/formattedtextfragmentcollection/collectiontype) { get; } | Obtient le type de collection de fragments formatés. |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Obtient le nombre d'éléments contenus dans la collection. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Obtient l'élément à l'index spécifié dans la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string) | Ajoute un fragment de texte formaté à la collection. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font) | Ajoute un fragment de texte formaté à la collection. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font, Color) | Ajoute un fragment de texte formaté à la collection. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font, Color, Color) | Ajoute un fragment de texte formaté à la collection. |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(FormattedTextFragment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(FormattedTextFragment) |  |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string) | Insère un fragment de texte formaté dans la collection à un indice donné. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font) | Insère un fragment de texte formaté dans la collection à un indice donné. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font, Color) | Insère un fragment de texte formaté dans la collection à un indice donné. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font, Color, Color) | Insère un fragment de texte formaté dans la collection à un indice donné. |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(FormattedTextFragment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Remarques

Cette collection contient les éléments du type [`PdfFormattedTextFragment`](../pdfformattedtextfragment).

### Voir aussi

* class [PdfFormattedTextFragmentCollection](../pdfformattedtextfragmentcollection)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
