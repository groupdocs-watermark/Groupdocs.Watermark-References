---
title: "EmailPreviewOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vistas previas del documento de Correo electrónico."
type: docs
weight: 17
url: /es/java/com.groupdocs.watermark.options/emailpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class EmailPreviewOptions extends PreviewOptions
```

Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vistas previas del documento de Correo electrónico.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EmailPreviewOptions(ICreatePageStream createPageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inicializa una nueva instancia de la clase `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` haciendo que el flujo de salida se cierre. |
|
|  | [EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inicializa una nueva instancia de la clase `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` haciendo que el flujo de salida se devuelva al cliente para su uso posterior. |
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
### EmailPreviewOptions(ICreatePageStream createPageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream)
```


Inicializa una nueva instancia de la clase `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` haciendo que el flujo de salida se cierre.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|

### EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la clase `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` haciendo que el flujo de salida se devuelva al cliente para su uso posterior.


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

El valor predeterminado es 96.

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

El valor predeterminado es 96.

<br />

|

