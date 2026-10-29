---
title: "PdfPreviewOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vista previa de un documento PDF."
type: docs
weight: 31
url: /es/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vista previa de un documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inicializa una nueva instancia de la clase `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` que hace que el flujo de salida se cierre. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inicializa una nueva instancia de la clase `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` que hace que el flujo de salida se devuelva al cliente para su uso posterior. |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Resolución predeterminada en puntos por pulgada. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getResolution()](#getResolution--) | Obtiene la resolución de las imágenes generadas, en puntos por pulgada. |
|
|  | [setResolution(int value)](#setResolution-int-) | Establece la resolución de las imágenes generadas, en puntos por pulgada. |
|
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Inicializa una nueva instancia de la clase `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` que hace que el flujo de salida se cierre.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la clase `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` que hace que el flujo de salida se devuelva al cliente para su uso posterior.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifica que la generación de la vista previa de la página ha finalizado y obtiene el flujo de salida. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Resolución predeterminada en puntos por pulgada.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Obtiene la resolución de las imágenes generadas, en puntos por pulgada.


**Returns:**
int - La resolución de las imágenes generadas, en puntos por pulgada.

<br />

*** ** * ** ***

El valor predeterminado es 150.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Establece la resolución de las imágenes generadas, en puntos por pulgada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La resolución de las imágenes generadas, en puntos por pulgada. |

<br />

*** ** * ** ***

El valor predeterminado es 150.

<br />

|

