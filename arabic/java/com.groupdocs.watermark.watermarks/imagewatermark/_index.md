---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل علامة مائية صورة."
type: docs
weight: 13
url: /ar/java/com.groupdocs.watermark.watermarks/imagewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)

**All Implemented Interfaces:**
java.io.Closeable
```
public final class ImageWatermark extends Watermark implements Closeable
```

يمثل علامة مائية صورة.

**Learn more:**

* [Adding image watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+image+watermarks)

يوضح المثال التالي كيفية إضافة علامة مائية صورة إلى مستند من أي نوع مدعوم.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>    watermarker.add(watermark);
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ImageWatermark(String filePath)](#ImageWatermark-java.lang.String-) | يُنشئ مثيلاً جديداً للفئة `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` بمسار ملف محدد. |
|
|  | [ImageWatermark(InputStream stream)](#ImageWatermark-java.io.InputStream-) | يُنشئ مثيلاً جديداً للفئة `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` بتدفق محدد. |
|
| [ImageWatermark(System.IO.Stream stream)](#ImageWatermark-com.aspose.ms.System.IO.Stream-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getStream()](#getStream--) |  |
| [getTransparentImageContainer()](#getTransparentImageContainer--) |  |
| [getSize()](#getSize--) |  |
| [dispose()](#dispose--) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
|  | [close()](#close--) | يتخلص من النسخة الحالية. |
|
### ImageWatermark(String filePath) {#ImageWatermark-java.lang.String-}
```
public ImageWatermark(String filePath)
```


يُنشئ مثيلاً جديداً للفئة `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` بمسار ملف محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى الصورة التي ستُستخدم كعلامة مائية. |
|

### ImageWatermark(InputStream stream) {#ImageWatermark-java.io.InputStream-}
```
public ImageWatermark(InputStream stream)
```


يُنشئ مثيلاً جديداً للفئة `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` بتدفق محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | stream | java.io.InputStream | التدفق الذي يحتوي على الصورة التي ستُستخدم كعلامة مائية. |
|

### ImageWatermark(System.IO.Stream stream) {#ImageWatermark-com.aspose.ms.System.IO.Stream-}
```
public ImageWatermark(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### isImageWatermark() {#isImageWatermark--}
```
public boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public boolean isTextWatermark()
```




**Returns:**
boolean
### getStream() {#getStream--}
```
public final StreamContainer getStream()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getTransparentImageContainer() {#getTransparentImageContainer--}
```
public final StreamContainer getTransparentImageContainer()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getSize() {#getSize--}
```
public SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### dispose() {#dispose--}
```
public final void dispose()
```




### deepClone() {#deepClone--}
```
public Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
### close() {#close--}
```
public final void close()
```


يتخلص من النسخة الحالية.


