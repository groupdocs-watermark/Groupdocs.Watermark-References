---
title: "PresentationWatermarkSlideOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones al agregar una marca de agua a una diapositiva de documento de Presentación."
type: docs
weight: 46
url: /es/java/com.groupdocs.watermark.options/presentationwatermarkslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Representa opciones al agregar una marca de agua a una diapositiva de documento de Presentación.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua a una diapositiva específica de una presentación de Power Point.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.ppt", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>  
>    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
>    options.setSlideIndex(0);
>    options.setLocked(false); // default
>    options.setProtectWithUnreadableCharacters(false); // default
>    options.setName(null); // default
>    options.setAlternativeText(null); // default
>    
>    watermarker.save("C:\\Documents\\watermarked_test.ppt");
>    watermarker.close();
>  
> ```
> ````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PresentationWatermarkSlideOptions()](#PresentationWatermarkSlideOptions--) | Inicializa una nueva instancia de la clase `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSlideIndex()](#getSlideIndex--) | Obtiene el índice de la diapositiva a la que se añadirá la marca de agua. |
|
|  | [setSlideIndex(int value)](#setSlideIndex-int-) | Establece el índice de la diapositiva a la que se añadirá la marca de agua. |
|
### PresentationWatermarkSlideOptions() {#PresentationWatermarkSlideOptions--}
```
public PresentationWatermarkSlideOptions()
```


Inicializa una nueva instancia de la clase `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`.


### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Obtiene el índice de la diapositiva a la que se añadirá la marca de agua.


**Returns:**
int - El índice de la diapositiva a la que se añadirá la marca de agua.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


Establece el índice de la diapositiva a la que se añadirá la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de la diapositiva a la que se añadirá la marca de agua. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

