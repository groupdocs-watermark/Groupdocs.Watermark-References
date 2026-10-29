---
title: "SpreadsheetContent"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente un document Excel où un filigrane peut être placé."
type: docs
weight: 1170
url: /fr/net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
---
## SpreadsheetContent class

Représente un document Excel où un filigrane peut être placé.

```csharp
public class SpreadsheetContent : Content
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Worksheets](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets) { get; } | Obtient la collection de toutes les feuilles de calcul de ce [`SpreadsheetContent`](../spreadsheetcontent). |

## Méthodes

| Nom | Description |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt)() | Déchiffre le document. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Libère l'instance actuelle. |
| [Encrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt)(string) | Crypte le contenu. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trouve toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve les images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trouve tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Remarques

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)
* [Shapes in spreadsheet document](https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document)
* [Working with spreadsheet document attachments](https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments)
* [Working with worksheet backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds)
* [Working with worksheet headers and footers](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers)

### Exemples

Chargez et enregistrez le document Excel de tout type pris en charge.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.xls", loadOptions))
{
    // Utilisez la méthode Add pour ajouter un filigrane à une feuille de calcul particulière ou à toutes les feuilles.

    // Enregistrez les modifications.
    watermarker.Save(@"D:\output.xls");
}
```

### Voir aussi

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
