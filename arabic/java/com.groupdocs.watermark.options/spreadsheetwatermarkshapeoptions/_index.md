---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الخيارات عند إضافة علامة مائية شكل إلى ورقة عمل جدول بيانات."
type: docs
weight: 60
url: /ar/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)، [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)، [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

يمثل الخيارات عند إضافة علامة مائية شكل إلى ورقة عمل جدول بيانات.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

المثال التالي يوضح كيفية إضافة علامة مائية إلى ورقة عمل معينة في مستند Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
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
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | يُنشئ مثيلًا جديدًا لفئة `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | يحصل على فهرس ورقة العمل لإضافة العلامة المائية إليها. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | يضبط فهرس ورقة العمل لإضافة العلامة المائية إليها. |
|
|  | [getEffects()](#getEffects--) | يحصل على قيمة `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` أو `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | يحصل أو يضبط قيمة `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` أو `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


يُنشئ مثيلًا جديدًا لفئة `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`.


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

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


يحصل على قيمة `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` أو `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


يحصل أو يضبط قيمة `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` أو `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | الـ`[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` أو `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` للتأثيرات التي يجب تطبيقها على العلامة المائية. |
|

