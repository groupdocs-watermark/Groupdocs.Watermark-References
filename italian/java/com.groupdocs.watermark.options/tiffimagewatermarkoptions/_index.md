---
title: "TiffImageWatermarkOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine TIFF."
type: docs
weight: 63
url: /it/java/com.groupdocs.watermark.options/tiffimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class TiffImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine TIFF.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Il seguente esempio dimostra come aggiungere una filigrana a un fotogramma specifico di un'immagine TIFF.
>
> ````
> ```
>
>    TiffImageImageLoadOptions loadOptions = new TiffImageImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.tiff", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.tiff");
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TiffImageWatermarkOptions()](#TiffImageWatermarkOptions--) | Inizializza una nuova istanza della classe `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)`. |
|
|  | [TiffImageWatermarkOptions(int frameIndex)](#TiffImageWatermarkOptions-int-) | Inizializza una nuova istanza della classe `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` con un indice specificato del fotogramma. |
|
### TiffImageWatermarkOptions() {#TiffImageWatermarkOptions--}
```
public TiffImageWatermarkOptions()
```


Inizializza una nuova istanza della classe `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)`.


### TiffImageWatermarkOptions(int frameIndex) {#TiffImageWatermarkOptions-int-}
```
public TiffImageWatermarkOptions(int frameIndex)
```


Inizializza una nuova istanza della classe `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` con un indice specificato del fotogramma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | frameIndex | int | L'indice del frame a cui aggiungere la filigrana. |
|

