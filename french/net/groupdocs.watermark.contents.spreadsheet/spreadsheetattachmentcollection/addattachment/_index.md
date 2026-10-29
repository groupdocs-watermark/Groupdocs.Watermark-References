---
title: "AddAttachment"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Ajoute une pièce jointe au SpreadsheetWorksheetgroupdocs.watermark.contents.spreadsheet/spreadsheetworksheet."
type: docs
weight: 10
url: /fr/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment/
---
## SpreadsheetAttachmentCollection.AddAttachment method

Ajoute une pièce jointe au [`SpreadsheetWorksheet`](../../spreadsheetworksheet).

```csharp
public void AddAttachment(byte[] fileContent, string sourceFullName, byte[] previewImageContent, 
    double x, double y, double width, double height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileContent | Byte[] | Le contenu du fichier à joindre. |
| sourceFullName | String | Le nom complet du fichier joint (L'extension est utilisée pour déterminer l'application appropriée pour ouvrir le fichier). |
| previewImageContent | Byte[] | L'image d'aperçu du fichier joint sous forme de tableau d'octets. |
| x | Double | La coordonnée x du cadre de la pièce jointe (en points). |
| y | Double | La coordonnée y du cadre de la pièce jointe (en points). |
| width | Double | La largeur du cadre de la pièce jointe en points. |
| height | Double | La hauteur du cadre de la pièce jointe en points. |

### Voir aussi

* class [SpreadsheetAttachmentCollection](../../spreadsheetattachmentcollection)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
