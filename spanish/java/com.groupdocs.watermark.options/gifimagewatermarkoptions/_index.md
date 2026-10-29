---
title: "GifImageWatermarkOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua a una imagen GIF."
type: docs
weight: 21
url: /es/java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Representa opciones de adición de marca de agua al agregar una marca de agua a una imagen GIF.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

El siguiente ejemplo muestra cómo añadir una marca de agua a un fotograma concreto de una imagen GIF.
>
> ````
> ```
>
>    GifImageLoadOptions loadOptions = new GifImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
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
|  | [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | Inicializa una nueva instancia de la clase `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`. |
|
|  | [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | Inicializa una nueva instancia de la clase `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` con un índice especificado de un fotograma. |
|
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


Inicializa una nueva instancia de la clase `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`.


### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


Inicializa una nueva instancia de la clase `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` con un índice especificado de un fotograma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | frameIndex | int | El índice del fotograma al que se agregará la marca de agua. |
|

