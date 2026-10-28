---
title: "MultiframeImageWatermarkOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine multi-frame."
type: docs
weight: 26
url: /it/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine multi-frame.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Il seguente esempio dimostra come aggiungere una filigrana a un frame specifico di un'immagine multi-frame.
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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | Inizializza una nuova istanza della classe `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | Inizializza una nuova istanza della classe `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` con un indice specificato del frame. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | Ottiene l'indice del frame a cui aggiungere la filigrana. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | Imposta l'indice del frame a cui aggiungere la filigrana. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


Inizializza una nuova istanza della classe `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


Inizializza una nuova istanza della classe `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` con un indice specificato del frame.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | frameIndex | int | L'indice del frame a cui aggiungere la filigrana. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Ottiene l'indice del frame a cui aggiungere la filigrana.


**Returns:**
int - L'indice del frame a cui aggiungere la filigrana.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Imposta l'indice del frame a cui aggiungere la filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'indice del frame a cui aggiungere la filigrana. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

