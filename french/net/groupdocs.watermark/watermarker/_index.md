---
title: "Watermarker"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente une classe pour la gestion des filigranes dans un document."
type: docs
weight: 3140
url: /fr/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Représente une classe pour la gestion des filigranes dans un document.

```csharp
public class Watermarker : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Initialise une nouvelle instance de la classe [`Watermarker`](../watermarker) avec le flux spécifié. |
| [Watermarker](watermarker#constructor_4)(string) | Initialise une nouvelle instance de la classe [`Watermarker`](../watermarker) avec le chemin du document spécifié. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Initialise une nouvelle instance de la classe [`Watermarker`](../watermarker) avec le flux spécifié et les options de chargement. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Initialise une nouvelle instance de la classe [`Watermarker`](../watermarker) avec le flux spécifié et les paramètres. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Initialise une nouvelle instance de la classe [`Watermarker`](../watermarker) avec le chemin du document spécifié et les options de chargement. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Initialise une nouvelle instance de la classe [`Watermarker`](../watermarker) avec le chemin du document spécifié et les paramètres. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Initialise une nouvelle instance de la classe [`Watermarker`](../watermarker) avec le flux spécifié, les options de chargement et les paramètres. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Initialise une nouvelle instance de la classe [`Watermarker`](../watermarker) avec le chemin du document spécifié, les options de chargement et les paramètres. |

## Propriétés

| Nom | Description |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Obtient ou définit les objets de contenu qui doivent être inclus dans une recherche de filigrane. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Ajoute un filigrane au document chargé. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Ajoute un filigrane au document chargé en utilisant les options de filigrane. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Libère l'instance actuelle. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Génère des images d'aperçu pour le document. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Renvoie l'objet [`Content`](../../groupdocs.watermark.contents/content) pour le document chargé. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Obtient les informations sur le format du document chargé. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Trouve toutes les images dans le document. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Trouve les images selon les critères de recherche spécifiés. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Supprime le filigrane du document. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Supprime tous les filigranes de la collection du document. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Enregistre les données du document dans le flux sous-jacent. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Enregistre les données du document dans le flux sous-jacent en utilisant les options d'enregistrement. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Enregistre le document dans le flux spécifié. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Enregistre le document à l'emplacement de fichier spécifié. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Enregistre le document dans le flux spécifié en utilisant les options d'enregistrement. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Enregistre le document à l'emplacement de fichier spécifié en utilisant les options d'enregistrement. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Recherche toutes les filigranes possibles dans le document. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Recherche les filigranes possibles selon les critères de recherche spécifiés. |

### Exemples

Charge et enregistre un contenu dans n'importe quel format pris en charge.

```csharp
// Charge un contenu à partir d'un fichier.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Utilisez les méthodes de la classe Watermarker pour ajouter, rechercher ou supprimer des filigranes.

    // Enregistrez les modifications.
    watermarker.Save("D:\\output.pdf");
}
```

### Voir aussi

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
