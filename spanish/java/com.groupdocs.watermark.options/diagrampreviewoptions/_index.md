---
title: "DiagramPreviewOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vistas previas del documento de Diagrama."
type: docs
weight: 12
url: /es/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vistas previas del documento de Diagrama.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inicializa una nueva instancia de la clase `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` que provoca que el flujo de salida se cierre. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inicializa una nueva instancia de la clase `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` que hace que el flujo de salida se devuelva al cliente para su uso posterior. |
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
|  | [setResolution(float value)](#setResolution-float-) | Establece la resolución de las imágenes generadas, en puntos por pulgada. |
|
|  | [getHighQualityRendering()](#getHighQualityRendering--) | Obtiene la bandera para la renderización de alta calidad. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Establece la bandera para la renderización de alta calidad. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Inicializa una nueva instancia de la clase `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` que provoca que el flujo de salida se cierre.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la clase `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` que hace que el flujo de salida se devuelva al cliente para su uso posterior.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifica que la generación de la vista previa de la página ha finalizado y obtiene el flujo de salida. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Resolución predeterminada en puntos por pulgada.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


Obtiene la resolución de las imágenes generadas, en puntos por pulgada.


**Returns:**
float - La resolución de las imágenes generadas, en puntos por pulgada.

<br />

*** ** * ** ***

El valor predeterminado es 300.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Establece la resolución de las imágenes generadas, en puntos por pulgada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | La resolución de las imágenes generadas, en puntos por pulgada. |

<br />

*** ** * ** ***

El valor predeterminado es 300.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Obtiene la bandera para la renderización de alta calidad.


**Returns:**
boolean - La bandera para la renderización de alta calidad.

<br />

*** ** * ** ***

La renderización de alta calidad usa más recursos. El valor predeterminado es false.

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Establece la bandera para la renderización de alta calidad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | La bandera para la renderización de alta calidad. |

<br />

*** ** * ** ***

La renderización de alta calidad usa más recursos. El valor predeterminado es false.

<br />

|

