---
title: "PresentationWatermarkNoteSlideOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones al agregar una marca de agua a una diapositiva de nota de documento Presentation."
type: docs
weight: 44
url: /es/java/com.groupdocs.watermark.options/presentationwatermarknoteslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkNoteSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Representa opciones al agregar una marca de agua a una diapositiva de nota de documento Presentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Vea los ejemplos de uso en `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PresentationWatermarkNoteSlideOptions()](#PresentationWatermarkNoteSlideOptions--) | Inicializa una nueva instancia de la clase `[PresentationWatermarkNoteSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarknoteslideoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSlideIndex()](#getSlideIndex--) | Obtiene el índice de una diapositiva a la que se añadirá la marca de agua en su diapositiva de notas. |
|
|  | [setSlideIndex(int value)](#setSlideIndex-int-) | Establece el índice de una diapositiva a la que se añadirá la marca de agua en su diapositiva de notas. |
|
### PresentationWatermarkNoteSlideOptions() {#PresentationWatermarkNoteSlideOptions--}
```
public PresentationWatermarkNoteSlideOptions()
```


Inicializa una nueva instancia de la clase `[PresentationWatermarkNoteSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarknoteslideoptions)`.


### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Obtiene el índice de una diapositiva a la que se añadirá la marca de agua en su diapositiva de notas.


**Returns:**
int - El índice de la diapositiva a la que se añadirá la marca de agua en su diapositiva de notas.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


Establece el índice de una diapositiva a la que se añadirá la marca de agua en su diapositiva de notas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de la diapositiva a la que se añadirá la marca de agua en su diapositiva de notas. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

