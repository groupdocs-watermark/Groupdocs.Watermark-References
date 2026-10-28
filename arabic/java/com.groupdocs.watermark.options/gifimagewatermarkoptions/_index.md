---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة GIF."
type: docs
weight: 21
url: /ar/java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة GIF.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

المثال التالي يوضح كيفية إضافة علامة مائية إلى إطار معين من صورة GIF.
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


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | ينشئ مثيلاً جديداً من الفئة `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`. |
|
|  | [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | ينشئ مثيلاً جديداً من الفئة `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` مع فهرس محدد للإطار. |
|
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


ينشئ مثيلاً جديداً من الفئة `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`.


### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


ينشئ مثيلاً جديداً من الفئة `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` مع فهرس محدد للإطار.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | frameIndex | int | فهرس الإطار لإضافة العلامة المائية. |
|

