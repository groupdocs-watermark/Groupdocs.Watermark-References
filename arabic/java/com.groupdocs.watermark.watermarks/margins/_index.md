---
title: "Margins"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل إعدادات الهوامش لكل حافة من الكائن."
type: docs
weight: 15
url: /ar/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

يمثل إعدادات الهوامش لكل حافة من الكائن.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Margins()](#Margins--) | يُنشئ مثيلاً جديداً للفئة `[Margins](../../com.groupdocs.watermark.watermarks/margins)`. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | يقوم بإنشاء نسخة جديدة من الفئة `[Margins](../../com.groupdocs.watermark.watermarks/margins)` مع النوع والموقع والحجم المحددين. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | يحصل على `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | يضبط `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [getLeft()](#getLeft--) | يحصل على الهامش الأيسر. |
|
|  | [setLeft(double value)](#setLeft-double-) | يضبط الهامش الأيسر. |
|
|  | [getRight()](#getRight--) | يحصل على الهامش الأيمن. |
|
|  | [setRight(double value)](#setRight-double-) | يضبط الهامش الأيمن. |
|
|  | [getTop()](#getTop--) | يحصل على الهامش العلوي. |
|
|  | [setTop(double value)](#setTop-double-) | يضبط الهامش العلوي. |
|
|  | [getBottom()](#getBottom--) | يحصل على الهامش السفلي. |
|
|  | [setBottom(double value)](#setBottom-double-) | يضبط الهامش السفلي. |
|
### Margins() {#Margins--}
```
public Margins()
```


يُنشئ مثيلاً جديداً للفئة `[Margins](../../com.groupdocs.watermark.watermarks/margins)`.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


يقوم بإنشاء نسخة جديدة من الفئة `[Margins](../../com.groupdocs.watermark.watermarks/margins)` مع النوع والموقع والحجم المحددين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | marginType | int | الـ `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. يحدد كيفية تفسير قيم الهوامش. |
|
|  | يسار | double | قيمة الهامش الأيسر. |
|
|  | يمين | double | قيمة الهامش الأيمن. |
|
|  | أعلى | double | قيمة الهامش العلوي. |
|
|  | أسفل | double | قيمة الهامش السفلي. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


يحصل على `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. ضبط قيمة جديدة لهذه الخاصية يعيد تلقائيًا جميع الهوامش إلى قيمها الافتراضية (صفر).

القيمة الافتراضية هي `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - القيمة التي تحدد كيفية تفسير الهوامش.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


يضبط `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. ضبط قيمة جديدة لهذه الخاصية يعيد تلقائيًا جميع الهوامش إلى قيمها الافتراضية (صفر).

القيمة الافتراضية هي `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | القيمة التي تحدد كيفية تفسير الهوامش. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


يحصل على الهامش الأيسر.


**Returns:**
double - الإزاحة الأفقية من الحد الأيسر للعنصر الأصل.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


يضبط الهامش الأيسر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإزاحة الأفقية من الحد الأيسر للعنصر الأصل. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


يحصل على الهامش الأيمن.


**Returns:**
double - الإزاحة الأفقية من الحد الأيمن للعنصر الأصل.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


يضبط الهامش الأيمن.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإزاحة الأفقية من الحد الأيمن للعنصر الأصل. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


يحصل على الهامش العلوي.


**Returns:**
double - الإزاحة الأفقية من الحد العلوي للعنصر الأصل.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


يضبط الهامش العلوي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإزاحة الأفقية من الحد العلوي للعنصر الأصل. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


يحصل على الهامش السفلي.


**Returns:**
double - الإزاحة الأفقية من الحد السفلي للعنصر الأصل.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


يضبط الهامش السفلي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإزاحة الأفقية من الحد السفلي للعنصر الأصل. |
|

