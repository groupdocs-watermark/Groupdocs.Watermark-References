---
title: "WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند Word."
type: docs
weight: 73
url: /ar/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند Word.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isLocked()](#isLocked--) | يحصل على قيمة تشير إلى ما إذا كان تعديل الشكل في Word محظورًا. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | يضبط قيمة تشير إلى ما إذا كان تعديل الشكل في Word محظورًا. |
|
|  | [getLockType()](#getLockType--) | يحصل على نوع قفل العلامة المائية. |
|
|  | [setLockType(int value)](#setLockType-int-) | يضبط نوع قفل العلامة المائية. |
|
|  | [getPassword()](#getPassword--) | يحصل على كلمة مرور تُستخدم لقفل العلامة المائية. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يضبط كلمة مرور تُستخدم لقفل العلامة المائية. |
|
|  | [getName()](#getName--) | يحصل على اسم الشكل. |
|
|  | [setName(String value)](#setName-java.lang.String-) | يضبط اسم الشكل. |
|
|  | [getAlternativeText()](#getAlternativeText--) | يحصل على النص الوصفي (البديل) الذي سيُرتبط بالشكل. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | يضبط النص الوصفي (البديل) الذي سيُرتبط بالشكل. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


يحصل على قيمة تشير إلى ما إذا كان تعديل الشكل في Word محظورًا.


**Returns:**
منطقي - إذا كانت القيمة true ، سيتم حظر تعديل الشكل. بشكل افتراضي، القيمة هي false ، يمكن تعديل الشكل في Word.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان تعديل الشكل في Word محظورًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | إذا كانت القيمة true ، سيتم حظر تعديل الشكل. بشكل افتراضي، القيمة هي false ، يمكن تعديل الشكل في Word. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


يحصل على نوع قفل العلامة المائية.


**Returns:**
int - نوع قفل العلامة المائية `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


يضبط نوع قفل العلامة المائية.

القيمة `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` لا يمكن استخدامها مع
كائن من النوع `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | نوع قفل العلامة المائية `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل على كلمة مرور تُستخدم لقفل العلامة المائية.


**Returns:**
java.lang.String - كلمة مرور تُستخدم لقفل العلامة المائية.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يضبط كلمة مرور تُستخدم لقفل العلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | كلمة مرور تُستخدم لقفل العلامة المائية. |
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

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

