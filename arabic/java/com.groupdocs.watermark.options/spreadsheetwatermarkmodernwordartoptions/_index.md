---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الخيارات عند إضافة علامة مائية فن كلمة حديثة إلى ورقة عمل جدول بيانات."
type: docs
weight: 58
url: /ar/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)، [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)، [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

يمثل الخيارات عند إضافة علامة مائية فن كلمة حديثة إلى ورقة عمل جدول بيانات.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

المثال التالي يوضح كيفية إضافة علامة مائية WordArt حديثة إلى مستند Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setLocked(false); // default
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | ينشئ مثيلاً جديدًا للفئة `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | يحصل على فهرس ورقة العمل لإضافة العلامة المائية إليها. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | يضبط فهرس ورقة العمل لإضافة العلامة المائية إليها. |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


ينشئ مثيلاً جديدًا للفئة `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`.


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

