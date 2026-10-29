---
title: "EmailAttachmentCollection"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una colección de archivos adjuntos en un mensaje de correo electrónico."
type: docs
weight: 32
url: /es/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

Representa una colección de archivos adjuntos en un mensaje de correo electrónico.

Esta colección contiene los elementos de tipo `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)`.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Añade un adjunto al `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Añade un adjunto al `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileContent | byte[] | El contenido del archivo que se adjuntará. |
|
|  | name | java.lang.String | El nombre del archivo. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

