---
title: "SizingType"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يحدد كيفية حساب حجم العلامة المائية."
type: docs
weight: 16
url: /ar/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

يحدد كيفية حساب حجم العلامة المائية.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Auto](#Auto) | يجب أن يتم ضبط حجم العلامة المائية تلقائيًا وفقًا لمحتواها. |
|
|  | [Absolute](#Absolute) | يجب أن يتم ضبط حجم العلامة المائية إلى قيمة دقيقة `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
و `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | يجب أن يتم تحجيم العلامة المائية نسبةً إلى أبعاد العنصر الأصل باستخدام |
القيمة المحددة `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | يجب أن يتم تحجيم العلامة المائية نسبةً إلى مساحة العنصر الأصل باستخدام القيمة المحددة `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [toString(int value)](#toString-int-) | يعيد تمثيلًا نصيًا لقيمة `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | يحوّل سلسلة نصية إلى قيمة تعداد `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
### Auto {#Auto}
```
public static final int Auto
```


يجب أن يتم ضبط حجم العلامة المائية تلقائيًا وفقًا لمحتواها.


### Absolute {#Absolute}
```
public static final int Absolute
```


يجب أن يتم ضبط حجم العلامة المائية إلى قيمة دقيقة `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
و `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


يجب أن يتم تحجيم العلامة المائية نسبةً إلى أبعاد العنصر الأصل باستخدام
القيمة المحددة `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


يجب أن يتم تحجيم العلامة المائية نسبةً إلى مساحة العنصر الأصل باستخدام القيمة المحددة `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


يعيد تمثيلًا نصيًا لقيمة `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | القيمة المراد تحويلها. |
|

**Returns:**
java.lang.String - تمثيل النص لقيمة `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


يحوّل سلسلة نصية إلى قيمة تعداد `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | السلسلة المراد تحليلها. |
|

**Returns:**
int - قيمة تعداد `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

