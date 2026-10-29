---
title: "SpreadsheetPreviewOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vista previa de un documento de Spreadsheet."
type: docs
weight: 52
url: /es/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vista previa de un documento de Spreadsheet.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inicializa una nueva instancia de la clase `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` que hace que el flujo de salida se cierre. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inicializa una nueva instancia de la clase `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` que hace que el flujo de salida se devuelva al cliente para su uso posterior. |
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
|  | [getOnlyDataArea()](#getOnlyDataArea--) | Obtiene la bandera para renderizar solo el área de datos sin encabezados, pies de página ni márgenes. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | Establece la bandera para renderizar solo el área de datos sin encabezados, pies de página ni márgenes. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


Inicializa una nueva instancia de la clase `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` que hace que el flujo de salida se cierre.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la clase `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` que hace que el flujo de salida se devuelva al cliente para su uso posterior.


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

El valor predeterminado es 96.

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

El valor predeterminado es 96.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


Obtiene la bandera para renderizar solo el área de datos sin encabezados, pies de página ni márgenes.


**Returns:**
boolean - La bandera para renderizar solo el área de datos sin encabezados, pies de página ni márgenes.

<br />

*** ** * ** ***

Esta bandera hace que se renderice toda la hoja de cálculo en una sola página. El valor predeterminado es false.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


Establece la bandera para renderizar solo el área de datos sin encabezados, pies de página ni márgenes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | La bandera para renderizar solo el área de datos sin encabezados, pies de página ni márgenes. |

<br />

*** ** * ** ***

Esta bandera hace que se renderice toda la hoja de cálculo en una sola página. El valor predeterminado es false.

<br />

|

