---
title: "WordProcessingWatermarkPagesOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa las opciones al agregar la marca de agua a las páginas de un documento Word."
type: docs
weight: 76
url: /es/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Representa las opciones al agregar la marca de agua a las páginas de un documento Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua a una página específica de un documento Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Inicializa una nueva instancia de la clase `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | Obtiene los números de página a los que se añadirá la marca de agua. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Establece los números de página a los que se añadirá la marca de agua. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Inicializa una nueva instancia de la clase `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtiene los números de página a los que se añadirá la marca de agua.


**Returns:**
int[] - Los números de página a los que se añadirá la marca de agua.

<br />

*** ** * ** ***

Todos los números deben ser mayores o iguales a 1. Esta propiedad solo se usa al agregar la marca de agua a un documento. Si este valor es  null  o está vacío, la marca de agua se agrega a todas las páginas.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Establece los números de página a los que se añadirá la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int[] | Los números de página a los que se añadirá la marca de agua. |

<br />

*** ** * ** ***

Todos los números deben ser mayores o iguales a 1. Esta propiedad solo se usa al agregar la marca de agua a un documento. Si este valor es  null  o está vacío, la marca de agua se agrega a todas las páginas.

<br />

|

