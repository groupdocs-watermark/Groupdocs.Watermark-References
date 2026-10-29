---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente un fichier joint à un document Excel."
type: docs
weight: 1100
url: /fr/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

Représente un fichier joint à un document Excel.

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | Obtient ou définit le texte descriptif (alternatif) associé au fichier joint. |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | Obtient ou définit le contenu du fichier joint. |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | Obtient ou définit la hauteur du cadre de la pièce jointe en points. |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | Obtient une valeur indiquant si le contenu ne contient qu'un lien vers le fichier. |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | Obtient ou définit l'image d'aperçu du fichier joint sous forme de tableau d'octets. |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | Obtient le nom complet du fichier joint. |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | Obtient ou définit la largeur du cadre de la pièce jointe en points. |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | Obtient ou définit le décalage horizontal du cadre de la pièce jointe depuis la bordure gauche de la feuille de calcul en points. |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | Obtient ou définit le décalage vertical du cadre de la pièce jointe depuis la bordure supérieure de la feuille de calcul en points. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Charge un contenu depuis le fichier joint. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Charge un contenu depuis le fichier joint avec les options de chargement spécifiées. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Charge un contenu depuis le fichier joint avec les options de chargement et les paramètres spécifiés. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Obtient les informations sur un document stocké dans le fichier joint. |

### Voir aussi

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
