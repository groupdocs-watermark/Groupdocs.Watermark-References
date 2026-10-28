---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية توضيحية إلى مستند PDF."
type: docs
weight: 28
url: /ar/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية توضيحية إلى مستند PDF.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

المثال التالي يوضح كيفية إضافة علامة مائية لتعليق صورة إلى مستند PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | ينشئ مثيلاً جديدًا للفئة `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | يحصل على فهرس الصفحة لإضافة العلامة المائية إليها. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | يضبط فهرس الصفحة لإضافة العلامة المائية إليها. |
|
|  | [getPrintOnly()](#getPrintOnly--) | احصل على القيمة التي تشير إلى ما إذا كان سيتم طباعة التعليق، ولكن لا يتم عرضه في تطبيق عرض PDF. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | يضبط القيمة التي تشير إلى ما إذا كان سيتم طباعة التعليق، ولكن لا يتم عرضه في تطبيق عرض PDF. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


ينشئ مثيلاً جديدًا للفئة `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


يحصل على فهرس الصفحة لإضافة العلامة المائية إليها.


**Returns:**
int - فهرس الصفحة لإضافة العلامة المائية إليها.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


يضبط فهرس الصفحة لإضافة العلامة المائية إليها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | فهرس الصفحة لإضافة العلامة المائية إليها. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


احصل على القيمة التي تشير إلى ما إذا كان سيتم طباعة التعليق، ولكن لا يتم عرضه في تطبيق عرض PDF.


**Returns:**
منطقي - القيمة التي تشير إلى ما إذا كان سيتم طباعة التعليق، ولكن لا يتم عرضه في تطبيق عرض PDF.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


يضبط القيمة التي تشير إلى ما إذا كان سيتم طباعة التعليق، ولكن لا يتم عرضه في تطبيق عرض PDF.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | القيمة التي تشير إلى ما إذا كان سيتم طباعة التعليق، ولكن لا يتم عرضه في تطبيق عرض PDF. |
|

