---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الخيارات عند إضافة علامة مائية إلى شريحة مستند عرض تقديمي."
type: docs
weight: 46
url: /ar/java/com.groupdocs.watermark.options/presentationwatermarkslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkSlideOptions extends PresentationWatermarkBaseSlideOptions
```

يمثل الخيارات عند إضافة علامة مائية إلى شريحة مستند عرض تقديمي.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

يوضح المثال التالي كيفية إضافة علامة مائية إلى شريحة معينة من عرض Power Point.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.ppt", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>  
>    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
>    options.setSlideIndex(0);
>    options.setLocked(false); // default
>    options.setProtectWithUnreadableCharacters(false); // default
>    options.setName(null); // default
>    options.setAlternativeText(null); // default
>    
>    watermarker.save("C:\\Documents\\watermarked_test.ppt");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PresentationWatermarkSlideOptions()](#PresentationWatermarkSlideOptions--) | ينشئ مثيلًا جديدًا للفئة `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSlideIndex()](#getSlideIndex--) | يحصل على فهرس الشريحة لإضافة العلامة المائية إليها. |
|
|  | [setSlideIndex(int value)](#setSlideIndex-int-) | يضبط فهرس الشريحة لإضافة العلامة المائية إليها. |
|
### PresentationWatermarkSlideOptions() {#PresentationWatermarkSlideOptions--}
```
public PresentationWatermarkSlideOptions()
```


ينشئ مثيلًا جديدًا للفئة `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`.


### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


يحصل على فهرس الشريحة لإضافة العلامة المائية إليها.


**Returns:**
int - فهرس الشريحة لإضافة العلامة المائية إليها.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


يضبط فهرس الشريحة لإضافة العلامة المائية إليها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | فهرس الشريحة لإضافة العلامة المائية إليها. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

