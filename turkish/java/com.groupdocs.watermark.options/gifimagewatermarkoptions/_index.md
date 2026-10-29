---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir GIF görüntüsüne filigran eklenirken filigran ekleme seçeneklerini temsil eder."
type: docs
weight: 21
url: /tr/java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Bir GIF görüntüsüne filigran eklenirken filigran ekleme seçeneklerini temsil eder.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Aşağıdaki örnek, GIF görüntüsünün belirli bir çerçevesine filigran eklemenin nasıl yapılacağını gösterir.
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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` sınıfının yeni bir örneğini başlatır. |
|
|  | [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` sınıfının yeni bir örneğini, bir çerçevenin belirtilen indeksine göre başlatır. |
|
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


`[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` sınıfının yeni bir örneğini başlatır.


### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


`[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` sınıfının yeni bir örneğini, bir çerçevenin belirtilen indeksine göre başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | frameIndex | int | Filigran eklemek için çerçevenin indeksi. |
|

