---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Çok çerçeveli bir görüntüye filigran eklenirken filigran ekleme seçeneklerini temsil eder."
type: docs
weight: 26
url: /tr/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Çok çerçeveli bir görüntüye filigran eklenirken filigran ekleme seçeneklerini temsil eder.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Aşağıdaki örnek, çok çerçeveli bir görüntünün belirli bir çerçevesine filigran eklemeyi gösterir.
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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` sınıfının yeni bir örneğini başlatır. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` sınıfının, çerçevenin belirtilen indeksine sahip yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | Filigran eklemek için çerçevenin indeksini alır. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | Filigran eklemek için çerçevenin indeksini ayarlar. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


`[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` sınıfının yeni bir örneğini başlatır.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


`[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` sınıfının, çerçevenin belirtilen indeksine sahip yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | frameIndex | int | Filigran eklemek için çerçevenin indeksi. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Filigran eklemek için çerçevenin indeksini alır.


**Returns:**
int - Filigran eklemek için çerçevenin indeksi.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Filigran eklemek için çerçevenin indeksini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Filigran eklemek için çerçevenin indeksi. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

