---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند Presentation."
type: docs
weight: 39
url: /ar/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند Presentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

المثال التالي يوضح كيفية إضافة علامة مائية إلى شرائح الخدمة المختلفة في عرض تقديمي Power Point.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pptx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));
>
>    // Add watermark to all master slides
>    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
>    masterSlideOptions.setMasterSlideIndex(-1); // default
>    watermarker.add(watermark, masterSlideOptions);
>    
>    // Add watermark to all layout slides
>    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
>    layoutSlideOptions.setLayoutSlideIndex(-1); // default
>    watermarker.add(watermark, layoutSlideOptions);
>    
>    // Add watermark to all notes slides
>    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
>    noteSlideOptions.setSlideIndex(-1); // default
>    watermarker.add(watermark, noteSlideOptions);
>    
>    // Add watermark to handout master
>    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
>    watermarker.add(watermark, masterHandoutSlideOptions);
>    
>    // Add watermark to notes master
>    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
>    watermarker.add(watermark, masterNotesSlideOptions);
>    
>    watermarker.save("D:\\watermarked_test.pptx");
>    watermarker.close();
>  
> ```
> ````


## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isLocked()](#isLocked--) | يحصل على قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظورًا. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | يضبط قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظورًا. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. |
|
|  | [getName()](#getName--) | يحصل على اسم الشكل. |
|
|  | [setName(String value)](#setName-java.lang.String-) | يضبط اسم الشكل. |
|
|  | [getAlternativeText()](#getAlternativeText--) | يحصل على النص الوصفي (البديل) الذي سيُرتبط بالشكل. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | يضبط النص الوصفي (البديل) الذي سيُرتبط بالشكل. |
|
|  | [getEffects()](#getEffects--) | يحصل على قيمة `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` أو `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | يضبط قيمة `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` أو `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


يحصل على قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظورًا.


**Returns:**
منطقي - إذا كانت القيمة true، سيُحظر تحرير الشكل. بشكل افتراضي، القيمة false، يمكن تحرير الشكل في PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظورًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | إذا كانت القيمة true، سيُحظر تحرير الشكل. بشكل افتراضي، القيمة false، يمكن تحرير الشكل في PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة.

يتم تطبيق هذه الحماية فقط عندما تُعيد الدالة `#isLocked().isLocked()` القيمة `true`.


**Returns:**
boolean - قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة.

يتم تطبيق هذه الحماية فقط عندما تُعيد الدالة `#isLocked().isLocked()` القيمة `true`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. |
|

### getName() {#getName--}
```
public final String getName()
```


يحصل على اسم الشكل.


**Returns:**
java.lang.String - اسم الشكل.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يضبط اسم الشكل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | اسم الشكل. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


يحصل على النص الوصفي (البديل) الذي سيُرتبط بالشكل.


**Returns:**
java.lang.String - النص الوصفي (البديل) الذي سيتم ربطه بشكل.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


يضبط النص الوصفي (البديل) الذي سيُرتبط بالشكل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | النص الوصفي (البديل) الذي سيتم ربطه بشكل. |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


يحصل على قيمة `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` أو `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


يضبط قيمة `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` أو `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | قيمة `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` أو `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية. |
|

