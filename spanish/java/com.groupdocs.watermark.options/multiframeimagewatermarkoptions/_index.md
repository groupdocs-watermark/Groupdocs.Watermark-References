---
title: "MultiframeImageWatermarkOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua a una imagen multi-frame."
type: docs
weight: 26
url: /es/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Representa opciones de adición de marca de agua al agregar una marca de agua a una imagen multi-frame.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

El siguiente ejemplo muestra cómo agregar una marca de agua a un fotograma específico de una imagen multicuadro.
>
> ````
> ```
>
>    ImageLoadOptions loadOptions = new ImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.gif");
>    watermarker.close();
>  
> ```
> ````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | Inicializa una nueva instancia de la clase `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | Inicializa una nueva instancia de la clase `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` con un índice especificado del fotograma. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | Obtiene el índice del fotograma al que se agregará la marca de agua. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | Establece el índice del fotograma al que se agregará la marca de agua. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


Inicializa una nueva instancia de la clase `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


Inicializa una nueva instancia de la clase `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` con un índice especificado del fotograma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | frameIndex | int | El índice del fotograma al que se agregará la marca de agua. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Obtiene el índice del fotograma al que se agregará la marca de agua.


**Returns:**
int - El índice del fotograma al que se agregará la marca de agua.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Establece el índice del fotograma al que se agregará la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice del fotograma al que se agregará la marca de agua. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

