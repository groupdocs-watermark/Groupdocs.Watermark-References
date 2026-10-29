---
title: "PresentationWatermarkLayoutSlideOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones al agregar una marca de agua a una diapositiva de diseño de documento Presentation."
type: docs
weight: 40
url: /es/java/com.groupdocs.watermark.options/presentationwatermarklayoutslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkLayoutSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Representa opciones al agregar una marca de agua a una diapositiva de diseño de documento Presentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Vea los ejemplos de uso en `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PresentationWatermarkLayoutSlideOptions()](#PresentationWatermarkLayoutSlideOptions--) | Inicializa una nueva instancia de la clase `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getLayoutSlideIndex()](#getLayoutSlideIndex--) | Obtiene el índice de la diapositiva de diseño al que se añadirá la marca de agua. |
|
|  | [setLayoutSlideIndex(int value)](#setLayoutSlideIndex-int-) | Establece el índice de la diapositiva de diseño al que se añadirá la marca de agua. |
|
### PresentationWatermarkLayoutSlideOptions() {#PresentationWatermarkLayoutSlideOptions--}
```
public PresentationWatermarkLayoutSlideOptions()
```


Inicializa una nueva instancia de la clase `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)`.


### getLayoutSlideIndex() {#getLayoutSlideIndex--}
```
public final int getLayoutSlideIndex()
```


Obtiene el índice de la diapositiva de diseño al que se añadirá la marca de agua.


**Returns:**
int - El índice de la diapositiva de diseño al que se añadirá la marca de agua.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setLayoutSlideIndex(int value) {#setLayoutSlideIndex-int-}
```
public final void setLayoutSlideIndex(int value)
```


Establece el índice de la diapositiva de diseño al que se añadirá la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de la diapositiva de diseño al que se añadirá la marca de agua. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

