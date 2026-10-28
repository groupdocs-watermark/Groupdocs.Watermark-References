---
title: "GifImageWatermarkOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine GIF."
type: docs
weight: 21
url: /it/java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine GIF.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Il seguente esempio dimostra come aggiungere una filigrana a un fotogramma specifico di un'immagine GIF.
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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | Inizializza una nuova istanza della classe `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`. |
|
|  | [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | Inizializza una nuova istanza della classe `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` con un indice specificato di un fotogramma. |
|
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


Inizializza una nuova istanza della classe `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`.


### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


Inizializza una nuova istanza della classe `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` con un indice specificato di un fotogramma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | frameIndex | int | L'indice del frame a cui aggiungere la filigrana. |
|

