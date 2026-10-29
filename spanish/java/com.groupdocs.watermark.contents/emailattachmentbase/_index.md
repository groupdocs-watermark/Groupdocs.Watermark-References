---
title: "EmailAttachmentBase"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona una clase base para los archivos adjuntos de correo electrónico."
type: docs
weight: 31
url: /es/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

Proporciona una clase base para los archivos adjuntos de correo electrónico.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getContentId()](#getContentId--) | Obtiene el id de contenido de este `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getMediaType()](#getMediaType--) | Obtiene el tipo de medio de este `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getContent()](#getContent--) | Obtiene el contenido del archivo adjunto. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Establece el contenido del archivo adjunto. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Obtiene el id de contenido de este `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - El id de contenido de este `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Obtiene el tipo de medio de este `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - El tipo de medio de este `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getContent() {#getContent--}
```
public byte[] getContent()
```


Obtiene el contenido del archivo adjunto.


**Returns:**
byte[] - El contenido del archivo adjunto.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Establece el contenido del archivo adjunto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte[] | El contenido del archivo adjunto. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Obtiene un flujo del archivo adjunto.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Actualiza el archivo adjunto desde un flujo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

