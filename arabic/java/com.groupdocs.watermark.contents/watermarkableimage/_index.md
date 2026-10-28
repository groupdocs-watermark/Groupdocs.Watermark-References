---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل صورة داخل مستند."
type: docs
weight: 127
url: /ar/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

يمثل صورة داخل مستند.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

يوضح المثال التالي كيفية إضافة علامة مائية إلى جميع الصور داخل مستند من أي نوع مدعوم.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>  
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>  
>    // Find all images in the content.
>    WatermarkableImageCollection images = watermarker.getImages();
>  
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.add(watermark);
>    }
>  
>    // Save changes.
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع هذا `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` بالبكسل. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض هذا `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` بالبكسل. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | يضيف علامة مائية إلى هذا `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`. |
|
|  | [getBytes()](#getBytes--) | يحصل على الصورة كمصفوفة بايت. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع هذا `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` بالبكسل.


**Returns:**
int - ارتفاع هذا `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` بالبكسل.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض هذا `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` بالبكسل.


**Returns:**
int - عرض هذا `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` بالبكسل.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


يضيف علامة مائية إلى هذا `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`.

تفترض هذه الطريقة أن إزاحة العلامة المائية وحجمها يُقاسان بالبكسل (إذا تم تعيينهما).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | العلامة المائية لإضافتها إلى الصورة. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


يحصل على الصورة كمصفوفة بايت.


**Returns:**
byte[] - بيانات الصورة.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

