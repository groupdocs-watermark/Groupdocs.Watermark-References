---
title: "PreviewOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vista previa."
type: docs
weight: 47
url: /es/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vista previa.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inicializa una nueva instancia de la clase `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` que hace que el flujo de salida se cierre. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inicializa una nueva instancia de la clase `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` que hace que el flujo de salida se devuelva al cliente para su uso posterior. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtiene el ancho de vista previa de la página. |
|
|  | [setWidth(int value)](#setWidth-int-) | Establece el ancho de vista previa de la página. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de vista previa de la página. |
|
|  | [setHeight(int value)](#setHeight-int-) | Establece la altura de vista previa de la página. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Obtiene una matriz de números de página para generar vistas previas. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Establece una matriz de números de página para generar vistas previas. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Obtiene el formato de imagen de vista previa. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Establece el formato de imagen de vista previa. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | Obtiene una instancia de la clase de creación de flujo de página. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Establece una instancia de la clase de creación de flujo de página. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Obtiene una instancia de la clase de finalización de vista previa de página. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Establece una instancia de la clase de finalización de vista previa de página. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Inicializa una nueva instancia de la clase `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` que hace que el flujo de salida se cierre.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la clase `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` que hace que el flujo de salida se devuelva al cliente para su uso posterior.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea un flujo para una vista previa de página específica. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifica que la generación de la vista previa de la página ha finalizado y obtiene el flujo de salida. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de vista previa de la página.


**Returns:**
int - El ancho de vista previa de la página.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el ancho de vista previa de la página.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El ancho de vista previa de la página. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de vista previa de la página.


**Returns:**
int - La altura de vista previa de la página.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece la altura de vista previa de la página.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La altura de vista previa de la página. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtiene una matriz de números de página para generar vistas previas.


**Returns:**
int[] - La matriz de números de página para generar vistas previas.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Establece una matriz de números de página para generar vistas previas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int[] | La matriz de números de página para generar vistas previas. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Obtiene el formato de imagen de vista previa.


**Returns:**
int - El formato de imagen de vista previa.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Establece el formato de imagen de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El formato de imagen de vista previa. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Obtiene una instancia de la clase de creación de flujo de página.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Establece una instancia de la clase de creación de flujo de página.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | La instancia de la clase de creación de flujo de página. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Obtiene una instancia de la clase de finalización de vista previa de página.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Establece una instancia de la clase de finalización de vista previa de página.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | La instancia del delegado de finalización de vista previa de página. |
|

