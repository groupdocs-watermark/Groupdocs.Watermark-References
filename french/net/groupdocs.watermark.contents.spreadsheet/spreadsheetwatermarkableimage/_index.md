---
title: "SpreadsheetWatermarkableImage"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente une image à l'intérieur d'un document Excel."
type: docs
weight: 1320
url: /fr/net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/
---
## SpreadsheetWatermarkableImage class

Représente une image à l'intérieur d'un document Excel.

```csharp
public class SpreadsheetWatermarkableImage : WatermarkableImage
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetWatermarkableImage](spreadsheetwatermarkableimage)(byte[]) | Initialise une nouvelle instance de la classe [`SpreadsheetWatermarkableImage`](../spreadsheetwatermarkableimage) en utilisant les données d'image spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Obtient la hauteur de ce [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) en pixels. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Obtient la largeur de ce [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) en pixels. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Ajoute un filigrane à ce [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage). Cette méthode suppose que le décalage et la taille du filigrane sont mesurés en pixels (s'ils sont attribués). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trouve toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve les images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Obtient l'image sous forme de tableau d'octets. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trouve tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Voir aussi

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
