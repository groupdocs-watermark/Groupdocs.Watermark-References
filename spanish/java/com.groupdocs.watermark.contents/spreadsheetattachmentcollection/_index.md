---
title: "SpreadsheetAttachmentCollection"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una colección de archivos adjuntos en un documento de Excel."
type: docs
weight: 102
url: /es/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Representa una colección de archivos adjuntos en un documento de Excel.

Esta colección contiene los elementos de tipo `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)`.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Agrega un adjunto al `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Agrega un adjunto mediante un enlace (el documento no contendrá el contenido del archivo adjunto). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Agrega un adjunto al `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileContent | byte[] | El contenido del archivo que se adjuntará. |
|
|  | sourceFullName | java.lang.String | El nombre completo del archivo adjunto (La extensión se utiliza para determinar la aplicación adecuada para abrir el archivo). |
|
|  | previewImageContent | byte[] | La imagen de vista previa del archivo adjunto como una matriz de bytes. |
|
|  | x | double | La coordenada x del marco del adjunto (en puntos). |
|
|  | y | double | La coordenada y del marco del adjunto (en puntos). |
|
|  | ancho | double | El ancho del marco de adjunto en puntos. |
|
|  | altura | double | La altura del marco de adjunto en puntos. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Agrega un adjunto mediante un enlace (el documento no contendrá el contenido del archivo adjunto).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | La ruta del archivo vinculado. |
|
|  | previewImageContent | byte[] | La imagen de vista previa del archivo adjunto como una matriz de bytes. |
|
|  | x | double | La coordenada x del marco del adjunto (en puntos). |
|
|  | y | double | La coordenada y del marco del adjunto (en puntos). |
|
|  | ancho | double | El ancho del marco de adjunto en puntos. |
|
|  | altura | double | La altura del marco de adjunto en puntos. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

