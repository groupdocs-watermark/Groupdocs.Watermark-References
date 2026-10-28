---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une collection d'objets intégrés dans un message électronique."
type: docs
weight: 36
url: /fr/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

Représente une collection d'objets intégrés dans un message électronique.

Cette collection contient les éléments du type `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)`.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Ajoute une ressource intégrée au `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Ajoute une ressource intégrée au `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileContent | byte[] | Le contenu du fichier à ajouter. |
|
|  | name | java.lang.String | Le nom du fichier. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

