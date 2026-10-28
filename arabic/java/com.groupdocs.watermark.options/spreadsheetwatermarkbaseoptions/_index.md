---
title: "SpreadsheetWatermarkBaseOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند جدول بيانات."
type: docs
weight: 56
url: /ar/java/com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public abstract class SpreadsheetWatermarkBaseOptions extends SpreadsheetWatermarkOptions
```

الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند جدول بيانات.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isLocked()](#isLocked--) | يحصل على قيمة تشير إلى ما إذا كان تعديل الشكل في Excel محظوراً. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | يضبط قيمة تشير إلى ما إذا كان تعديل الشكل في Excel محظوراً. |
|
|  | [getName()](#getName--) | يحصل على اسم الشكل. |
|
|  | [setName(String value)](#setName-java.lang.String-) | يضبط اسم الشكل. |
|
|  | [getAlternativeText()](#getAlternativeText--) | يحصل على النص الوصفي (البديل) الذي سيُرتبط بالشكل. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | يضبط النص الوصفي (البديل) الذي سيُرتبط بالشكل. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


يحصل على قيمة تشير إلى ما إذا كان تعديل الشكل في Excel محظوراً.


**Returns:**
boolean - إذا كانت القيمة true، سيُحظر تعديل الشكل. بشكل افتراضي، القيمة false، يمكن تعديل الشكل في Excel.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان تعديل الشكل في Excel محظوراً.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | إذا كانت القيمة true، سيُحظر تعديل الشكل. بشكل افتراضي، القيمة false، يمكن تعديل الشكل في Excel. |
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

