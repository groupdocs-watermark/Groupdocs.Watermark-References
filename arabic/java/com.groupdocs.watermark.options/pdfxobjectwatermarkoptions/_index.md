---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية XObject إلى مستند PDF."
type: docs
weight: 34
url: /ar/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية XObject إلى مستند PDF.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

المثال التالي يوضح كيفية إضافة علامة مائية إلى صفحة معينة من مستند pdf.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | ينشئ مثيلاً جديداً من الفئة `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | يحصل على فهرس الصفحة لإضافة العلامة المائية إليها. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | يضبط فهرس الصفحة لإضافة العلامة المائية إليها. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


ينشئ مثيلاً جديداً من الفئة `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`.


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

