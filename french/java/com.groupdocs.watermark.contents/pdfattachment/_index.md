---
title: "PdfAttachment"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un fichier joint à un contenu PDF."
type: docs
weight: 58
url: /fr/java/com.groupdocs.watermark.contents/pdfattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public class PdfAttachment extends Attachment
```

Représente un fichier joint à un contenu PDF.

**Learn more:**

* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Obtient le nom du fichier joint. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Définit le nom du fichier joint. |
|
|  | [getDescription()](#getDescription--) | Obtient la description du fichier joint. |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | Définit la description du fichier joint. |
|
|  | [getContent()](#getContent--) | Obtient le contenu du fichier joint. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Définit le contenu du fichier joint. |
|
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
| [getContentStream()](#getContentStream--) |  |
### getName() {#getName--}
```
public final String getName()
```


Obtient le nom du fichier joint.


**Returns:**
java.lang.String - Le nom du fichier joint.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Définit le nom du fichier joint.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nom du fichier joint. |
|

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Obtient la description du fichier joint.


**Returns:**
java.lang.String - La description du fichier joint.

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Définit la description du fichier joint.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | La description du fichier joint. |
|

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

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Met à jour le fichier joint à partir d'un flux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Obtient un flux depuis le fichier joint.


**Returns:**
com.aspose.ms.System.IO.Stream
