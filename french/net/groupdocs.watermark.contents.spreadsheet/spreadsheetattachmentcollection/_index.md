---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente une collection de pièces jointes dans un document Excel."
type: docs
weight: 1110
url: /fr/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/
---
## SpreadsheetAttachmentCollection class

Représente une collection de pièces jointes dans un document Excel.

```csharp
public class SpreadsheetAttachmentCollection : RemoveOnlyListBase<SpreadsheetAttachment>
```

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Obtient le nombre d'éléments contenus dans la collection. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Obtient l'élément à l'index spécifié dans la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddAttachment](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment)(byte[], string, byte[], double, double, double, double) | Ajoute une pièce jointe à la [`SpreadsheetWorksheet`](../spreadsheetworksheet). |
| [AddLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink)(string, byte[], double, double, double, double) | Ajoute une pièce jointe via un lien (le document ne contiendra pas le contenu du fichier joint). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(SpreadsheetAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(SpreadsheetAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(SpreadsheetAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Remarques

Cette collection contient les éléments de type [`SpreadsheetAttachment`](../spreadsheetattachment).

### Voir aussi

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [SpreadsheetAttachment](../spreadsheetattachment)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
