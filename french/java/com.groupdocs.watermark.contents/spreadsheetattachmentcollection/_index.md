---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une collection de pièces jointes dans un document Excel."
type: docs
weight: 102
url: /fr/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Représente une collection de pièces jointes dans un document Excel.

Cette collection contient les éléments de type `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)`.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Ajoute une pièce jointe au `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Ajoute une pièce jointe via un lien (le document ne contiendra pas le contenu du fichier joint). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Ajoute une pièce jointe au `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileContent | byte[] | Le contenu du fichier à joindre. |
|
|  | sourceFullName | java.lang.String | Le nom complet du fichier joint (l'extension est utilisée pour déterminer l'application appropriée pour ouvrir le fichier). |
|
|  | previewImageContent | byte[] | L'image d'aperçu du fichier joint sous forme de tableau d'octets. |
|
|  | x | double | La coordonnée x du cadre de la pièce jointe (en points). |
|
|  | y | double | La coordonnée y du cadre de la pièce jointe (en points). |
|
|  | largeur | double | La largeur du cadre de la pièce jointe en points. |
|
|  | hauteur | double | La hauteur du cadre de la pièce jointe en points. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Ajoute une pièce jointe via un lien (le document ne contiendra pas le contenu du fichier joint).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | Le chemin du fichier lié. |
|
|  | previewImageContent | byte[] | L'image d'aperçu du fichier joint sous forme de tableau d'octets. |
|
|  | x | double | La coordonnée x du cadre de la pièce jointe (en points). |
|
|  | y | double | La coordonnée y du cadre de la pièce jointe (en points). |
|
|  | largeur | double | La largeur du cadre de la pièce jointe en points. |
|
|  | hauteur | double | La hauteur du cadre de la pièce jointe en points. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

