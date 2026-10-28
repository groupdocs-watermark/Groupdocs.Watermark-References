---
title: "OfficeLineFormat"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل تنسيق خط الشكل."
type: docs
weight: 47
url: /ar/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

يمثل تنسيق خط الشكل.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | ينشئ مثيلاً جديداً للفئة `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWeight()](#getWeight--) | يحصل على سمك الفرشاة التي ترسم مسار الشكل. |
|
|  | [setWeight(double value)](#setWeight-double-) | يضبط سمك الفرشاة التي ترسم مسار الشكل. |
|
|  | [getColor()](#getColor--) | يحصل على لون الخط. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | يضبط لون الخط. |
|
|  | [getOpacity()](#getOpacity--) | يحصل على شفافية الخط. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | يضبط شفافية الخط. |
|
|  | [getEnabled()](#getEnabled--) | يحصل على قيمة تشير إلى ما إذا كان الشكل سيُرسم. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | يضبط قيمة تشير إلى ما إذا كان الشكل سيُرسم. |
|
|  | [getDashStyle()](#getDashStyle--) | يحصل على نمط النقاط والشرطات للخط. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | يضبط نمط النقاط والشرطات للخط. |
|
|  | [getLineStyle()](#getLineStyle--) | يحصل على نمط الخط. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | يضبط نمط الخط. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


ينشئ مثيلاً جديداً للفئة `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


يحصل على سمك الفرشاة التي ترسم مسار الشكل.


**Returns:**
double - سمك الخط بالنقاط. القيمة الافتراضية هي 0.75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


يضبط سمك الفرشاة التي ترسم مسار الشكل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | سمك الخط بالنقاط. القيمة الافتراضية هي 0.75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


يحصل على لون الخط.

القيمة الافتراضية هي `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


يضبط لون الخط.

القيمة الافتراضية هي `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | لون الخط. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


يحصل على شفافية الخط.


**Returns:**
double - يجب أن تكون القيمة بين 0 و 1. القيمة الافتراضية هي 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


يضبط شفافية الخط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | يجب أن تكون القيمة بين 0 و 1. القيمة الافتراضية هي 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


يحصل على قيمة تشير إلى ما إذا كان الشكل سيُرسم.


**Returns:**
منطقي - القيمة الافتراضية هي false.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان الشكل سيُرسم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | القيمة الافتراضية هي false. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


يحصل على نمط النقاط والشرطات للخط.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


يضبط نمط النقاط والشرطات للخط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


يحصل على نمط الخط.

القيمة الافتراضية هي `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Returns:**
int - نمط الخط.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


يضبط نمط الخط.

القيمة الافتراضية هي `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | نمط الخط. |
|

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


<br />



**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```


<br />



**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
