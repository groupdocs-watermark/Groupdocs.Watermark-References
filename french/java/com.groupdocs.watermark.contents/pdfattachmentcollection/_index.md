---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une collection de pièces jointes dans un document PDF."
type: docs
weight: 59
url: /fr/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

Représente une collection de pièces jointes dans un document PDF.

Cette collection contient les éléments de type `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)`.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | Ajoute une pièce jointe au `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


Ajoute une pièce jointe au `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileContent | byte[] | Le contenu du fichier à joindre. |
|
|  | name | java.lang.String | Le nom du fichier. |
|
|  | description | java.lang.String | La description du fichier. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

