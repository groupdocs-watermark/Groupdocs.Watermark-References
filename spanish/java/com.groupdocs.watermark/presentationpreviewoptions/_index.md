---
title: "PresentationPreviewOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vistas previas del documento de Presentación."
type: docs
weight: 12
url: /es/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vistas previas del documento de Presentación.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inicializa una nueva instancia de la clase `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` provocando que el flujo de salida se cierre. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inicializa una nueva instancia de la clase `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` provocando que el flujo de salida se devuelva al cliente para su uso posterior. |
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
|  | [setResolution(long value)](#setResolution-long-) | Establece la resolución de las imágenes generadas, en puntos por pulgada. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


Inicializa una nueva instancia de la clase `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` provocando que el flujo de salida se cierre.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la clase `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` provocando que el flujo de salida se devuelva al cliente para su uso posterior.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifica que la generación de la vista previa de la página ha finalizado y obtiene el flujo de salida. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Resolución predeterminada en puntos por pulgada.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


Obtiene la resolución de las imágenes generadas, en puntos por pulgada.


**Returns:**
long - La resolución de las imágenes generadas, en puntos por pulgada.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Establece la resolución de las imágenes generadas, en puntos por pulgada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | long | La resolución de las imágenes generadas, en puntos por pulgada. |
|

