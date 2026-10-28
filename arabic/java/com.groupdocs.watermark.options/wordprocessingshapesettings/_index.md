---
title: "WordProcessingShapeSettings"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الإعدادات التي يمكن تطبيقها على علامة مائية شكل لمستند Word."
type: docs
weight: 71
url: /ar/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

يمثل الإعدادات التي يمكن تطبيقها على علامة مائية شكل لمستند Word.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | ينشئ مثيلاً جديدًا للفئة `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`. |
|
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
|  | [getPageNumbers()](#getPageNumbers--) | يحصل على أرقام الصفحات لإضافة العلامة المائية. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | يضبط أرقام الصفحات لإضافة العلامة المائية. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


ينشئ مثيلاً جديدًا للفئة `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`.


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
int - نوع قفل العلامة المائية لـ `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

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
|  | value | int | نوع قفل العلامة المائية لـ `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
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

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


يحصل على أرقام الصفحات لإضافة العلامة المائية.


**Returns:**
int[] - أرقام الصفحات لإضافة العلامة المائية.

<br />

*** ** * ** ***

يجب أن تكون جميع الأرقام أكبر من أو تساوي 1. تُستخدم هذه الخاصية فقط عند إضافة العلامة المائية إلى مستند. إذا كانت هذه القيمة null ، تُضاف العلامة المائية إلى جميع الصفحات.

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

يجب أن تكون جميع الأرقام أكبر من أو تساوي 1. تُستخدم هذه الخاصية فقط عند إضافة العلامة المائية إلى مستند. إذا كانت هذه القيمة null ، تُضاف العلامة المائية إلى جميع الصفحات.

<br />

|

