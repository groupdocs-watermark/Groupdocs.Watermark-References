---
title: "EmailAttachmentBase"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit une classe de base pour les pièces jointes d'e-mail."
type: docs
weight: 31
url: /fr/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

Fournit une classe de base pour les pièces jointes d'e-mail.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getContentId()](#getContentId--) | Obtient l'identifiant de contenu de ce `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getMediaType()](#getMediaType--) | Obtient le type média de ce `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getContent()](#getContent--) | Obtient le contenu du fichier joint. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Définit le contenu du fichier joint. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Obtient l'identifiant de contenu de ce `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - L'identifiant de contenu de ce `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Obtient le type média de ce `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - Le type média de ce `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getContent() {#getContent--}
```
public byte[] getContent()
```


Obtient le contenu du fichier joint.


**Returns:**
byte[] - Le contenu du fichier joint.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Définit le contenu du fichier joint.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | byte[] | Le contenu du fichier joint. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Obtient un flux depuis le fichier joint.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Met à jour le fichier joint à partir d'un flux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

