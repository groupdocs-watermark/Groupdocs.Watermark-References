---
title: "Attachment"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un archivo adjunto a un documento."
type: docs
weight: 10
url: /es/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Representa un archivo adjunto a un documento.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | Obtiene la información sobre un documento almacenado en el archivo adjunto. |
|
|  | [getContent()](#getContent--) | Obtiene el contenido del archivo adjunto. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Establece el contenido del archivo adjunto. |
|
|  | [createWatermarker()](#createWatermarker--) | Carga un contenido del archivo adjunto. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Carga un contenido del archivo adjunto con las opciones de carga especificadas. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Carga un contenido del archivo adjunto con las opciones de carga y configuraciones especificadas. |
|
|  | [getContentStream()](#getContentStream--) | Obtiene un flujo del archivo adjunto. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Actualiza el archivo adjunto desde un flujo. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Actualiza el contenido adjunto. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtiene la información sobre un documento almacenado en el archivo adjunto.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Obtiene el contenido del archivo adjunto.


**Returns:**
byte[] - El contenido del archivo adjunto.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Establece el contenido del archivo adjunto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte[] | El contenido del archivo adjunto. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Carga un contenido del archivo adjunto.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Carga un contenido del archivo adjunto con las opciones de carga especificadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opciones adicionales para usar al cargar el contenido de un adjunto. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Carga un contenido del archivo adjunto con las opciones de carga y configuraciones especificadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opciones adicionales para usar al cargar el contenido de un adjunto. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Configuraciones adicionales para usar al trabajar con el documento cargado. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Obtiene un flujo del archivo adjunto.


**Returns:**
com.aspose.ms.System.IO.Stream - El flujo para leer el contenido del archivo.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Actualiza el archivo adjunto desde un flujo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | El flujo para actualizar el archivo adjunto. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Actualiza el contenido adjunto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | La versión actualizada del contenido. |
|

