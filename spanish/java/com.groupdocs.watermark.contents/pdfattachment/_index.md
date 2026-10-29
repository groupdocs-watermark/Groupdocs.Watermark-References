---
title: "PdfAttachment"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un archivo adjunto a un contenido pdf."
type: docs
weight: 58
url: /es/java/com.groupdocs.watermark.contents/pdfattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public class PdfAttachment extends Attachment
```

Representa un archivo adjunto a un contenido pdf.

**Learn more:**

* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Obtiene el nombre del archivo adjunto. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Establece el nombre del archivo adjunto. |
|
|  | [getDescription()](#getDescription--) | Obtiene la descripción del archivo adjunto. |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | Establece la descripción del archivo adjunto. |
|
|  | [getContent()](#getContent--) | Obtiene el contenido del archivo adjunto. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Establece el contenido del archivo adjunto. |
|
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
| [getContentStream()](#getContentStream--) |  |
### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre del archivo adjunto.


**Returns:**
java.lang.String - El nombre del archivo adjunto.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Establece el nombre del archivo adjunto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nombre del archivo adjunto. |
|

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Obtiene la descripción del archivo adjunto.


**Returns:**
java.lang.String - La descripción del archivo adjunto.

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Establece la descripción del archivo adjunto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La descripción del archivo adjunto. |
|

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

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Actualiza el archivo adjunto desde un flujo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Obtiene un flujo del archivo adjunto.


**Returns:**
com.aspose.ms.System.IO.Stream
