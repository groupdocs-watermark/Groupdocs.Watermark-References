---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة TIFF."
type: docs
weight: 63
url: /ar/java/com.groupdocs.watermark.options/tiffimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class TiffImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة TIFF.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

المثال التالي يوضح كيفية إضافة علامة مائية إلى إطار معين من صورة TIFF.
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


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TiffImageWatermarkOptions()](#TiffImageWatermarkOptions--) | ينشئ مثيلاً جديداً من الفئة `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)`. |
|
|  | [TiffImageWatermarkOptions(int frameIndex)](#TiffImageWatermarkOptions-int-) | ينشئ مثيلاً جديداً من الفئة `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` مع فهرس محدد للإطار. |
|
### TiffImageWatermarkOptions() {#TiffImageWatermarkOptions--}
```
public TiffImageWatermarkOptions()
```


ينشئ مثيلاً جديداً من الفئة `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)`.


### TiffImageWatermarkOptions(int frameIndex) {#TiffImageWatermarkOptions-int-}
```
public TiffImageWatermarkOptions(int frameIndex)
```


ينشئ مثيلاً جديداً من الفئة `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` مع فهرس محدد للإطار.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | frameIndex | int | فهرس الإطار لإضافة العلامة المائية. |
|

