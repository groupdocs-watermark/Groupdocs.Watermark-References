---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الخيارات عند إضافة علامة مائية إلى الشريحة الرئيسية لمستند Presentation."
type: docs
weight: 43
url: /ar/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

يمثل الخيارات عند إضافة علامة مائية إلى الشريحة الرئيسية لمستند Presentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

انظر أمثلة الاستخدام في `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | ينشئ مثيلاً جديدًا للفئة `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | يحصل على فهرس الشريحة الرئيسية لإضافة العلامة المائية إليها. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | يضبط فهرس الشريحة الرئيسية لإضافة العلامة المائية إليها. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


ينشئ مثيلاً جديدًا للفئة `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


يحصل على فهرس الشريحة الرئيسية لإضافة العلامة المائية إليها.


**Returns:**
عدد صحيح - فهرس الشريحة الرئيسية لإضافة العلامة المائية إليها.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


يضبط فهرس الشريحة الرئيسية لإضافة العلامة المائية إليها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | فهرس الشريحة الرئيسية لإضافة العلامة المائية إليها. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

