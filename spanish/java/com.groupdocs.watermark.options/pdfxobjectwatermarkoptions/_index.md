---
title: "PdfXObjectWatermarkOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua XObject a un documento pdf."
type: docs
weight: 34
url: /es/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

Representa opciones de adición de marca de agua al agregar una marca de agua XObject a un documento pdf.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua a una página específica de un documento pdf.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | Inicializa una nueva instancia de la clase `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Obtiene el índice de página al que se añadirá la marca de agua. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Establece el índice de página al que se añadirá la marca de agua. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


Inicializa una nueva instancia de la clase `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Obtiene el índice de página al que se añadirá la marca de agua.


**Returns:**
int - El índice de página al que se añadirá la marca de agua.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Establece el índice de página al que se añadirá la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de página al que se añadirá la marca de agua. |
|

