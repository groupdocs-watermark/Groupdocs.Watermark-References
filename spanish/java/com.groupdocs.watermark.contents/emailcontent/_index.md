---
title: "EmailContent"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un mensaje de correo electrónico."
type: docs
weight: 34
url: /es/java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

Representa un mensaje de correo electrónico.

**Learn more:**

* [Add watermarks to email attachments](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments)
* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Email messages](../https://docs.groupdocs.com/display/watermarkjava/Email+messages)

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAttachments()](#getAttachments--) | Obtiene la colección de todos los archivos adjuntos del mensaje de correo electrónico. |
|
|  | [getEmbeddedObjects()](#getEmbeddedObjects--) | Obtiene la colección de todos los objetos incrustados del mensaje de correo electrónico. |
|
|  | [getFrom()](#getFrom--) | Obtiene la dirección del remitente del mensaje de correo electrónico. |
|
|  | [getTo()](#getTo--) | Obtiene la colección de destinatarios del mensaje de correo electrónico. |
|
|  | [getCc()](#getCc--) | Obtiene la colección de destinatarios CC (copia carbón) del mensaje de correo electrónico. |
|
|  | [getBcc()](#getBcc--) | Obtiene la colección de destinatarios BCC (copia carbón oculta) del mensaje de correo electrónico. |
|
|  | [getSubject()](#getSubject--) | Obtiene el asunto del mensaje de correo electrónico. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Establece el asunto del mensaje de correo electrónico. |
|
|  | [getBody()](#getBody--) | Obtiene la representación en texto plano del cuerpo del mensaje. |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | Establece la representación en texto plano del cuerpo del mensaje. |
|
|  | [getHtmlBody()](#getHtmlBody--) | Obtiene la representación HTML del cuerpo del mensaje. |
|
|  | [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Establece la representación HTML del cuerpo del mensaje. |
|
|  | [getBodyType()](#getBodyType--) | Obtiene el tipo del cuerpo del mensaje de correo electrónico. |
|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | <br /> |

|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings) {#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| fileFormatInfo | com.aspose.email.FileFormatInfo |  |
| emailLoadOptions | [EmailLoadOptions](../../com.groupdocs.watermark.options/emailloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getAttachments() {#getAttachments--}
```
public final EmailAttachmentCollection getAttachments()
```


Obtiene la colección de todos los archivos adjuntos del mensaje de correo electrónico.


**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.

### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


Obtiene la colección de todos los objetos incrustados del mensaje de correo electrónico.


**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.

### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


Obtiene la dirección del remitente del mensaje de correo electrónico.


**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.

### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


Obtiene la colección de destinatarios del mensaje de correo electrónico.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.

### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


Obtiene la colección de destinatarios CC (copia carbón) del mensaje de correo electrónico.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.

### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


Obtiene la colección de destinatarios BCC (copia carbón oculta) del mensaje de correo electrónico.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Obtiene el asunto del mensaje de correo electrónico.


**Returns:**
java.lang.String - El asunto del mensaje de correo electrónico.

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Establece el asunto del mensaje de correo electrónico.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El asunto del mensaje de correo electrónico. |
|

### getBody() {#getBody--}
```
public final String getBody()
```


Obtiene la representación en texto plano del cuerpo del mensaje.


**Returns:**
java.lang.String - La representación en texto plano del cuerpo del mensaje.

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Establece la representación en texto plano del cuerpo del mensaje.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La representación de texto sin formato del cuerpo del mensaje. |
|

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


Obtiene la representación HTML del cuerpo del mensaje.


**Returns:**
java.lang.String - La representación html del cuerpo del mensaje.

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


Establece la representación HTML del cuerpo del mensaje.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La representación html del cuerpo del mensaje. |
|

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Obtiene el tipo del cuerpo del mensaje de correo electrónico.


**Returns:**
int - El tipo del cuerpo del mensaje de correo electrónico.

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public IDocumentInfo getDocumentInfo()
```


<br />



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
### getFileType() {#getFileType--}
```
public FileType getFileType()
```


<br />



**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype)
### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

