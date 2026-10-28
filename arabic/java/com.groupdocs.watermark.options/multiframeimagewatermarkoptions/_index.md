---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة متعددة الإطارات."
type: docs
weight: 26
url: /ar/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة متعددة الإطارات.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

المثال التالي يوضح كيفية إضافة علامة مائية إلى إطار معين من صورة متعددة الإطارات.
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


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | يُنشئ مثيلًا جديدًا لفئة `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | يُنشئ مثيلًا جديدًا لفئة `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` مع فهرس محدد للإطار. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | يحصل على فهرس الإطار لإضافة العلامة المائية. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | يضبط فهرس الإطار لإضافة العلامة المائية. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


يُنشئ مثيلًا جديدًا لفئة `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


يُنشئ مثيلًا جديدًا لفئة `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` مع فهرس محدد للإطار.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | frameIndex | int | فهرس الإطار لإضافة العلامة المائية. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


يحصل على فهرس الإطار لإضافة العلامة المائية.


**Returns:**
int - فهرس الإطار لإضافة العلامة المائية.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


يضبط فهرس الإطار لإضافة العلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | فهرس الإطار لإضافة العلامة المائية. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

