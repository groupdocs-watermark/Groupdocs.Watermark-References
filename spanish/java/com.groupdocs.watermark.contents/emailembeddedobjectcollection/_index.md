---
title: "EmailEmbeddedObjectCollection"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una colección de objetos incrustados en un mensaje de correo electrónico."
type: docs
weight: 36
url: /es/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

Representa una colección de objetos incrustados en un mensaje de correo electrónico.

Esta colección contiene los elementos del tipo `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)`.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Agrega un recurso incrustado al `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Agrega un recurso incrustado al `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileContent | byte[] | El contenido del archivo a agregar. |
|
|  | name | java.lang.String | El nombre del archivo. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

