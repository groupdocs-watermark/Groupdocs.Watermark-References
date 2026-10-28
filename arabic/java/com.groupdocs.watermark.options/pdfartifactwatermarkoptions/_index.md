---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية للقطعة إلى مستند PDF."
type: docs
weight: 29
url: /ar/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية للقطعة إلى مستند PDF.

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

المثال التالي يوضح كيفية إضافة علامة مائية كقطعة صورة إلى مستند PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
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
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | ينشئ مثيلاً جديداً من الفئة `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | يحصل على فهرس الصفحة لإضافة العلامة المائية إليها. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | يضبط فهرس الصفحة لإضافة العلامة المائية إليها. |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


ينشئ مثيلاً جديداً من الفئة `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


يحصل على فهرس الصفحة لإضافة العلامة المائية إليها.


**Returns:**
int - فهرس الصفحة لإضافة العلامة المائية إليها.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


يضبط فهرس الصفحة لإضافة العلامة المائية إليها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | فهرس الصفحة لإضافة العلامة المائية إليها. |
|

