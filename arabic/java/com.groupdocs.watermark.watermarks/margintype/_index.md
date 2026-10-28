---
title: "MarginType"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يحدد كيفية تفسير قيم الهوامش."
type: docs
weight: 14
url: /ar/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

يحدد كيفية تفسير قيم الهوامش.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Absolute](#Absolute) | قيمة الهامش مقاسة بوحدات المحتوى. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | يجب تفسير قيمة الهامش كجزء من البُعد المناسب للعنصر الأصل. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | يجب تفسير قيمة الهامش كجزء من الحد الأدنى لبُعد العنصر الأصل. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [toString(int value)](#toString-int-) | إرجاع تمثيل نصي لقيمة `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | تحويل سلسلة إلى قيمة تعداد `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


قيمة الهامش مقاسة بوحدات المحتوى.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


يجب تفسير قيمة الهامش كجزء من البُعد المناسب للعنصر الأصل.


الهامشان الأيسر والأيمن نسبيان إلى عرض العنصر الأصل،
الهامشان العلوي والسفلي نسبيان إلى ارتفاع العنصر الأصل.
إذا تم اختيار هذا النوع، يجب أن تكون قيمة الهامش بين 0.0 و 1.0.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


يجب تفسير قيمة الهامش كجزء من الحد الأدنى لبُعد العنصر الأصل.


إذا تم اختيار هذا النوع، يجب أن تكون قيمة الهامش بين 0.0 و 1.0.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


إرجاع تمثيل نصي لقيمة `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | القيمة المراد تحويلها. |
|

**Returns:**
java.lang.String - تمثيل النص لقيمة `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


تحويل سلسلة إلى قيمة تعداد `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | السلسلة المراد تحليلها. |
|

**Returns:**
int - قيمة تعداد `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

