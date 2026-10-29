---
title: "WordProcessingWatermarkSectionOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa las opciones al agregar una marca de agua de forma a una sección de documento Word."
type: docs
weight: 77
url: /es/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Representa las opciones al agregar una marca de agua de forma a una sección de documento Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua a una sección particular de un documento de Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
>    options.setSectionIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | Inicializa una nueva instancia de la clase `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Obtiene el índice de una sección a la que se añadirá la marca de agua. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Establece el índice de una sección a la que se añadirá la marca de agua. |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


Inicializa una nueva instancia de la clase `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Obtiene el índice de una sección a la que se añadirá la marca de agua.


**Returns:**
int - El índice de una sección al que se añadirá la marca de agua.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Establece el índice de una sección a la que se añadirá la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de una sección al que se añadirá la marca de agua. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

