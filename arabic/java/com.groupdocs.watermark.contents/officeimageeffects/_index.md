---
title: "OfficeImageEffects"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل التأثيرات التي يمكن تطبيقها على علامة مائية للصورة في محتوى Office."
type: docs
weight: 45
url: /ar/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

يمثل التأثيرات التي يمكن تطبيقها على علامة مائية للصورة في محتوى Office.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | يحصل على إعدادات تنسيق الخط لحدود الصورة. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | يضبط إعدادات تنسيق الخط لحدود الصورة. |
|
|  | [getGrayScale()](#getGrayScale--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة ستُعرض بوضع الرمادي. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | يضبط قيمة تشير إلى ما إذا كانت الصورة ستُعرض بوضع الرمادي. |
|
|  | [getChromaKey()](#getChromaKey--) | يحصل على قيمة اللون للصورة التي ستُعامل كشفافة. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | يضبط قيمة اللون للصورة التي ستُعامل كشفافة. |
|
|  | [getBrightness()](#getBrightness--) | يحصل على سطوع الصورة. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | يضبط سطوع الصورة. |
|
|  | [getContrast()](#getContrast--) | يحصل على التباين للصورة المحددة. |
|
|  | [setContrast(double value)](#setContrast-double-) | يضبط التباين للصورة المحددة. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


يحصل على إعدادات تنسيق الخط لحدود الصورة.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


يضبط إعدادات تنسيق الخط لحدود الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | مثيل لفئة OfficeLineFormat، تمثّل تنسيق خط الشكل. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة ستُعرض بوضع الرمادي.


**Returns:**
منطقي - القيمة الافتراضية هي false.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت الصورة ستُعرض بوضع الرمادي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | القيمة الافتراضية هي false. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


يحصل على قيمة اللون للصورة التي ستُعامل كشفافة.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


يضبط قيمة اللون للصورة التي ستُعامل كشفافة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | القيمة الافتراضية هي لون شفاف بالكامل. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


يحصل على سطوع الصورة. يجب أن تكون القيمة لهذه الخاصية
رقماً من 0.0 (أكثر قتامة) إلى 1.0 (أكثر سطوع).


**Returns:**
double - القيمة الافتراضية هي 0.5.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


يضبط سطوع الصورة. يجب أن تكون القيمة لهذه الخاصية
رقماً من 0.0 (أكثر قتامة) إلى 1.0 (أكثر سطوع).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | القيمة الافتراضية هي 0.5. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


يحصل على التباين للصورة المحددة. القيمة لهذه الخاصية
يجب أن يكون رقماً من 0.0 (أقل تباين) إلى 1.0 (أعلى تباين).


**Returns:**
double - القيمة الافتراضية هي 0.5.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


يضبط التباين للصورة المحددة. القيمة لهذه الخاصية
يجب أن يكون رقماً من 0.0 (أقل تباين) إلى 1.0 (أعلى تباين).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | القيمة الافتراضية هي 0.5. |
|

