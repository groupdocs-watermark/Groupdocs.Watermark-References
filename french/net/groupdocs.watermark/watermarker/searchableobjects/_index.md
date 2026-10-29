---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Obtient ou définit les objets de contenu qui doivent être inclus dans une recherche de filigrane."
type: docs
weight: 20
url: /fr/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

Obtient ou définit les objets de contenu qui doivent être inclus dans une recherche de filigrane.

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

Les objets qui doivent être inclus dans une recherche de filigrane.

### Remarques

Cette propriété spécifie également les objets de contenu utilisés dans la recherche d'images. Pour plus d'informations, voir les méthodes [`Search`](../search) et [`GetImages`](../getimages).

En savoir plus sur la recherche de filigranes : [Recherche de filigranes](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Exemples

Supprimer tous les XObjects et Artifacts d'un document PDF.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // Spécifier que seuls les XObjects et Artifacts doivent être recherchés.
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // Supprimer tous les objets trouvés.
    watermarks.Clear();

    // Enregistrez les modifications.
    watermarker.Save();
}
```

### Voir aussi

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
