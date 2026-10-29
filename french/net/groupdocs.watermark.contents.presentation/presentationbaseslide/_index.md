---
title: "PresentationBaseSlide"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Fournit la classe de base abstraite pour les diapositives de tous types dans un document PowerPoint."
type: docs
weight: 870
url: /fr/net/groupdocs.watermark.contents.presentation/presentationbaseslide/
---
## PresentationBaseSlide class

Fournit la classe de base abstraite pour les diapositives de tous types dans un document PowerPoint.

```csharp
public abstract class PresentationBaseSlide : ContentPart
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Charts](../../groupdocs.watermark.contents.presentation/presentationbaseslide/charts) { get; } | Obtient la collection de tous les graphiques de la présentation. |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseslide/imagefillformat) { get; } | Obtient les paramètres du format de remplissage d'image de la présentation. |
| [Shapes](../../groupdocs.watermark.contents.presentation/presentationbaseslide/shapes) { get; } | Obtient la collection de toutes les formes de la présentation. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trouve toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve les images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trouve tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Voir aussi

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
