---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones al agregar una marca de agua a una diapositiva maestra de documento Presentation."
type: docs
weight: 43
url: /es/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Representa opciones al agregar una marca de agua a una diapositiva maestra de documento Presentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Vea los ejemplos de uso en `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Inicializa una nueva instancia de la clase `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | Obtiene el índice de la diapositiva maestra a la que se agregará la marca de agua. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Establece el índice de la diapositiva maestra a la que se agregará la marca de agua. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Inicializa una nueva instancia de la clase `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Obtiene el índice de la diapositiva maestra a la que se agregará la marca de agua.


**Returns:**
int - El índice de la diapositiva maestra a la que se agregará la marca de agua.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Establece el índice de la diapositiva maestra a la que se agregará la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de la diapositiva maestra a la que se agregará la marca de agua. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

