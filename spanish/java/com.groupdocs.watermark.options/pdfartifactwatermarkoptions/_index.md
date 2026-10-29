---
title: "PdfArtifactWatermarkOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua de artefacto a un documento pdf."
type: docs
weight: 29
url: /es/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

Representa opciones de adición de marca de agua al agregar una marca de agua de artefacto a un documento pdf.

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua de artefacto de imagen a un documento PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
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
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | Inicializa una nueva instancia de la clase `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Obtiene el índice de página al que se añadirá la marca de agua. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Establece el índice de página al que se añadirá la marca de agua. |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


Inicializa una nueva instancia de la clase `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`.


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

