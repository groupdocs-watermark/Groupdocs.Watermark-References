---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الخيارات عند إضافة العلامة المائية إلى ترويسة/تذييل جدول البيانات."
type: docs
weight: 57
url: /ar/java/com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetWatermarkHeaderFooterOptions extends SpreadsheetWatermarkOptions
```

يمثل الخيارات عند إضافة العلامة المائية إلى ترويسة/تذييل جدول البيانات.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

المثال التالي يوضح كيفية إضافة علامة مائية نصية إلى رأس ورقة عمل Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetWatermarkHeaderFooterOptions()](#SpreadsheetWatermarkHeaderFooterOptions--) | ينشئ مثيلاً جديدًا للفئة `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | يحصل على فهرس ورقة العمل لإضافة العلامة المائية إليها. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | يضبط فهرس ورقة العمل لإضافة العلامة المائية إليها. |
|
### SpreadsheetWatermarkHeaderFooterOptions() {#SpreadsheetWatermarkHeaderFooterOptions--}
```
public SpreadsheetWatermarkHeaderFooterOptions()
```


ينشئ مثيلاً جديدًا للفئة `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


يحصل على فهرس ورقة العمل لإضافة العلامة المائية إليها.


**Returns:**
int - فهرس ورقة العمل لإضافة العلامة المائية إليها.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


يضبط فهرس ورقة العمل لإضافة العلامة المائية إليها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | فهرس ورقة العمل لإضافة العلامة المائية إليها. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

