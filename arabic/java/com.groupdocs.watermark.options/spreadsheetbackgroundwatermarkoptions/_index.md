---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الخيارات عند إضافة العلامة المائية كخلفية إلى ورقة عمل جدول بيانات."
type: docs
weight: 49
url: /ar/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

يمثل الخيارات عند إضافة العلامة المائية كخلفية إلى ورقة عمل جدول بيانات.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

المثال التالي يوضح كيفية إضافة علامة مائية نصية إلى ورقة عمل مستند Excel كخلفية.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
>
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | ينشئ مثيلاً جديدًا للفئة `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | احصل على فهرس ورقة العمل لإضافة العلامة المائية إليها. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | يضبط فهرس ورقة العمل لإضافة العلامة المائية إليها. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | احصل على العرض المطلوب لصورة الخلفية بالبكسل. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | يضبط العرض المطلوب لصورة الخلفية بالبكسل. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | يحصل أو يضبط الارتفاع المطلوب لصورة الخلفية بالبكسل. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | يحصل أو يضبط الارتفاع المطلوب لصورة الخلفية بالبكسل. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


ينشئ مثيلاً جديدًا للفئة `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


احصل على فهرس ورقة العمل لإضافة العلامة المائية إليها.

-1 means every worksheet.


**Returns:**
int - فهرس ورقة العمل لإضافة العلامة المائية إليها.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


يضبط فهرس ورقة العمل لإضافة العلامة المائية إليها.

-1 means every worksheet.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | فهرس ورقة العمل لإضافة العلامة المائية إليها. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


احصل على العرض المطلوب لصورة الخلفية بالبكسل.


**Returns:**
int - العرض المطلوب لصورة الخلفية بالبكسل.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


يضبط العرض المطلوب لصورة الخلفية بالبكسل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | العرض المطلوب لصورة الخلفية بالبكسل. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


يحصل أو يضبط الارتفاع المطلوب لصورة الخلفية بالبكسل.


**Returns:**
int - الارتفاع المطلوب لصورة الخلفية بالبكسل.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


يحصل أو يضبط الارتفاع المطلوب لصورة الخلفية بالبكسل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | الارتفاع المطلوب لصورة الخلفية بالبكسل. |
|

