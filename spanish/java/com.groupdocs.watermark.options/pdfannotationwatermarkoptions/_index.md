---
title: "PdfAnnotationWatermarkOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua de anotación a un documento pdf."
type: docs
weight: 28
url: /es/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

Representa opciones de adición de marca de agua al agregar una marca de agua de anotación a un documento pdf.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua de anotación de imagen a un documento PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Inicializa una nueva instancia de la clase `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Obtiene el índice de página al que se añadirá la marca de agua. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Establece el índice de página al que se añadirá la marca de agua. |
|
|  | [getPrintOnly()](#getPrintOnly--) | Obtenga el valor que indica si la anotación se imprimirá, pero no se mostrará en la aplicación de visualización de PDF. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Establece el valor que indica si la anotación se imprimirá, pero no se mostrará en la aplicación de visualización de PDF. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Inicializa una nueva instancia de la clase `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Obtiene el índice de página al que se añadirá la marca de agua.


**Returns:**
int - El índice de página al que se añadirá la marca de agua.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Establece el índice de página al que se añadirá la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de página al que se añadirá la marca de agua. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Obtenga el valor que indica si la anotación se imprimirá, pero no se mostrará en la aplicación de visualización de PDF.


**Returns:**
boolean - El valor que indica si la anotación se imprimirá, pero no se mostrará en la aplicación de visualización de PDF.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Establece el valor que indica si la anotación se imprimirá, pero no se mostrará en la aplicación de visualización de PDF.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | El valor que indica si la anotación se imprimirá, pero no se mostrará en la aplicación de visualización de PDF. |
|

