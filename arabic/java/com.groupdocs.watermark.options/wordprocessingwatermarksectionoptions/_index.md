---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الخيارات عند إضافة علامة مائية على شكل إلى قسم مستند Word."
type: docs
weight: 77
url: /ar/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

يمثل الخيارات عند إضافة علامة مائية على شكل إلى قسم مستند Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

يوضح المثال التالي كيفية إضافة علامة مائية إلى قسم معين من مستند Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
>    options.setSectionIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | ينشئ مثيلاً جديدًا للفئة `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | يحصل على فهرس القسم لإضافة العلامة المائية إليه. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | يضبط فهرس القسم لإضافة العلامة المائية إليه. |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


ينشئ مثيلاً جديدًا للفئة `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


يحصل على فهرس القسم لإضافة العلامة المائية إليه.


**Returns:**
int - الفهرس لقسم لإضافة العلامة المائية إليه.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


يضبط فهرس القسم لإضافة العلامة المائية إليه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | الفهرس لقسم لإضافة العلامة المائية إليه. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

