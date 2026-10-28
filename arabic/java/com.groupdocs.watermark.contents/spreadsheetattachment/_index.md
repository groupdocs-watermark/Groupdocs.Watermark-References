---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل ملفًا مرفقًا بمستند Excel."
type: docs
weight: 101
url: /ar/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

يمثل ملفًا مرفقًا بمستند Excel.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getContent()](#getContent--) | يحصل على محتوى الملف المرفق. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | يضبط محتوى الملف المرفق. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | يسترجع صورة معاينة الملف المرفق كمصفوفة بايت. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | يضبط صورة معاينة الملف المرفق كمصفوفة بايت. |
|
|  | [isLink()](#isLink--) | يسترجع قيمة تشير إلى ما إذا كان المحتوى يحتوي فقط على رابط للملف. |
|
|  | [getSourceFullName()](#getSourceFullName--) | يسترجع الاسم الكامل للملف المرفق. |
|
|  | [getAlternativeText()](#getAlternativeText--) | يسترجع النص الوصفي (البديل) المرتبط بالملف المرفق. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | يضبط النص الوصفي (البديل) المرتبط بالملف المرفق. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | يسترجع الإزاحة الأفقية لإطار المرفق من الحد الأيسر للورقة بالنقاط. |
|
|  | [setX(double value)](#setX-double-) | يضبط الإزاحة الأفقية لإطار المرفق من الحد الأيسر للورقة بالنقاط. |
|
|  | [getY()](#getY--) | يسترجع الإزاحة العمودية لإطار المرفق من الحد العلوي للورقة بالنقاط. |
|
|  | [setY(double value)](#setY-double-) | يضبط الإزاحة العمودية لإطار المرفق من الحد العلوي للورقة بالنقاط. |
|
|  | [getWidth()](#getWidth--) | يسترجع عرض إطار المرفق بالنقاط. |
|
|  | [setWidth(double value)](#setWidth-double-) | يضبط عرض إطار المرفق بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يسترجع ارتفاع إطار المرفق بالنقاط. |
|
|  | [setHeight(double value)](#setHeight-double-) | يضبط ارتفاع إطار المرفق بالنقاط. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


يحصل على محتوى الملف المرفق.


**Returns:**
byte[] - محتوى الملف المرفق.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


يضبط محتوى الملف المرفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | byte[] | محتوى الملف المرفق. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


يسترجع صورة معاينة الملف المرفق كمصفوفة بايت.


**Returns:**
byte[] - صورة معاينة الملف المرفق كمصفوفة بايت.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


يضبط صورة معاينة الملف المرفق كمصفوفة بايت.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | byte[] | صورة معاينة الملف المرفق كمصفوفة بايت. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


يسترجع قيمة تشير إلى ما إذا كان المحتوى يحتوي فقط على رابط للملف.


**Returns:**
boolean - صحيح إذا كان الملف المرفق مُشارًا إليه عبر رابط (المحتوى لا يحتوي على محتوى الملف المرفق)؛ وإلا، خطأ.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


يسترجع الاسم الكامل للملف المرفق.


**Returns:**
java.lang.String - الاسم الكامل للملف المرفق.

<br />

*** ** * ** ***

يُستخدم الامتداد لتحديد التطبيق المناسب لفتح الملف.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


يسترجع النص الوصفي (البديل) المرتبط بالملف المرفق.


**Returns:**
java.lang.String - النص الوصفي (البديل) المرتبط بالملف المرفق.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


يضبط النص الوصفي (البديل) المرتبط بالملف المرفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | النص الوصفي (البديل) المرتبط بالملف المرفق. |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


يسترجع الإزاحة الأفقية لإطار المرفق من الحد الأيسر للورقة بالنقاط.


**Returns:**
double - الإحداثي السيني لإطار المرفق.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


يضبط الإزاحة الأفقية لإطار المرفق من الحد الأيسر للورقة بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإحداثي السيني لإطار المرفق. |
|

### getY() {#getY--}
```
public final double getY()
```


يسترجع الإزاحة العمودية لإطار المرفق من الحد العلوي للورقة بالنقاط.


**Returns:**
double - الإحداثي الصادي لإطار المرفق.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


يضبط الإزاحة العمودية لإطار المرفق من الحد العلوي للورقة بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإحداثي الصادي لإطار المرفق. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


يسترجع عرض إطار المرفق بالنقاط.


**Returns:**
double - عرض إطار المرفق بالنقاط.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


يضبط عرض إطار المرفق بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | عرض إطار المرفق بالنقاط. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


يسترجع ارتفاع إطار المرفق بالنقاط.


**Returns:**
double - ارتفاع إطار المرفق بالنقاط.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


يضبط ارتفاع إطار المرفق بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | ارتفاع إطار المرفق بالنقاط. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



