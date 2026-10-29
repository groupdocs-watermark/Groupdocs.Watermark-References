---
title: "PresentationContent"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente un document PowerPoint où un filigrane peut être placé."
type: docs
weight: 900
url: /fr/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

Représente un document PowerPoint où un filigrane peut être placé.

```csharp
public class PresentationContent : Content
```

## Propriétés

| Nom | Description |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | Obtient la collection de toutes les diapositives de mise en page de ce [`PresentationContent`](../presentationcontent). |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | Obtient la diapositive principale du support de ce [`PresentationContent`](../presentationcontent). |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | Obtient la diapositive maîtresse pour toutes les diapositives de notes de ce [`PresentationContent`](../presentationcontent). |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | Obtient la collection de toutes les diapositives maîtresses de ce [`PresentationContent`](../presentationcontent). |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | Obtient la hauteur d’une diapositive de notes en points. |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | Obtient la largeur d’une diapositive de notes en points. |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | Obtient la hauteur d’une diapositive en points. |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | Obtient la collection de toutes les diapositives de ce [`PresentationContent`](../presentationcontent). |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | Obtient la largeur d’une diapositive en points. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | Déchiffre le document. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Libère l'instance actuelle. |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | Crypte le document. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trouve toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve les images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trouve tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Remarques

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### Exemples

Chargez et enregistrez un document PowerPoint de tout type pris en charge.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // Utilisez la méthode Add pour ajouter un filigrane à une diapositive particulière ou à toutes les diapositives.

    // Enregistrez les modifications.
    watermarker.Save(@"D:\output.ppt");
}
```

### Voir aussi

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
