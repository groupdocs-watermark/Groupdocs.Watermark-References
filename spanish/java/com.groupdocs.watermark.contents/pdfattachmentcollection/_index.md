---
title: "PdfAttachmentCollection"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una colección de adjuntos en un documento pdf."
type: docs
weight: 59
url: /es/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

Representa una colección de adjuntos en un documento pdf.

Esta colección contiene los elementos del tipo `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)`.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | Agrega un adjunto al `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


Agrega un adjunto al `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileContent | byte[] | El contenido del archivo que se adjuntará. |
|
|  | name | java.lang.String | El nombre del archivo. |
|
|  | description | java.lang.String | La descripción del archivo. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

