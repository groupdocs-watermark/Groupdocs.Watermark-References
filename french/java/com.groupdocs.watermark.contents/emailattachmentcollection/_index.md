---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une collection de pièces jointes dans un message électronique."
type: docs
weight: 32
url: /fr/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

Représente une collection de pièces jointes dans un message électronique.

Cette collection contient les éléments de type `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)`.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Ajoute une pièce jointe au `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Ajoute une pièce jointe au `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileContent | byte[] | Le contenu du fichier à joindre. |
|
|  | name | java.lang.String | Le nom du fichier. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

