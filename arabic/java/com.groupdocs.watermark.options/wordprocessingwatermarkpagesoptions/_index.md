---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الخيارات عند إضافة العلامة المائية إلى صفحات مستند Word."
type: docs
weight: 76
url: /ar/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

يمثل الخيارات عند إضافة العلامة المائية إلى صفحات مستند Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

المثال التالي يوضح كيفية إضافة علامة مائية إلى صفحة معينة من مستند Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | ينشئ مثيلاً جديداً من الفئة `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | يحصل على أرقام الصفحات لإضافة العلامة المائية. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | يضبط أرقام الصفحات لإضافة العلامة المائية. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


ينشئ مثيلاً جديداً من الفئة `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


يحصل على أرقام الصفحات لإضافة العلامة المائية.


**Returns:**
int[] - أرقام الصفحات لإضافة العلامة المائية.

<br />

*** ** * ** ***

يجب أن تكون جميع الأرقام أكبر من أو تساوي 1. تُستخدم هذه الخاصية فقط عند إضافة العلامة المائية إلى مستند. إذا كانت هذه القيمة  null  أو فارغة، تُضاف العلامة المائية إلى جميع الصفحات.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


يضبط أرقام الصفحات لإضافة العلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int[] | أرقام الصفحات لإضافة العلامة المائية. |

<br />

*** ** * ** ***

يجب أن تكون جميع الأرقام أكبر من أو تساوي 1. تُستخدم هذه الخاصية فقط عند إضافة العلامة المائية إلى مستند. إذا كانت هذه القيمة  null  أو فارغة، تُضاف العلامة المائية إلى جميع الصفحات.

<br />

|

