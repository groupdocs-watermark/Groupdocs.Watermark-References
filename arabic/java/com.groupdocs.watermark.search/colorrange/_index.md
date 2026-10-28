---
title: "ColorRange"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل نطاقًا من الألوان."
type: docs
weight: 12
url: /ar/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

يمثل نطاقًا من الألوان. يحدد النطاقات باستخدام تمثيل HSB للون RGB.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | يُنشئ مثيلًا جديدًا من الفئة `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | يُنشئ مثيلًا جديدًا من الفئة `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` بلون محدد دقيق. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | يحصل على قيمة درجة اللون الابتدائية، بالدرجات. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | يضبط قيمة درجة اللون الابتدائية، بالدرجات. |
|
|  | [getMaxHue()](#getMaxHue--) | يحصل على قيمة درجة اللون النهائية، بالدرجات. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | يضبط قيمة درجة اللون النهائية، بالدرجات. |
|
|  | [getMinSaturation()](#getMinSaturation--) | يحصل على قيمة التشبع الابتدائية. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | يضبط قيمة التشبع الابتدائية. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | يحصل على قيمة التشبع النهائية. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | يضبط قيمة التشبع النهائية. |
|
|  | [getMinBrightness()](#getMinBrightness--) | يحصل على قيمة السطوع الابتدائية. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | يضبط قيمة السطوع الابتدائية. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | يحصل على قيمة السطوع النهائية. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | يضبط قيمة السطوع النهائية. |
|
|  | [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان اللون الفارغ فقط ضمن النطاق. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | يضبط قيمة تشير إلى ما إذا كان اللون الفارغ فقط ضمن النطاق. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


يُنشئ مثيلًا جديدًا من الفئة `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


يُنشئ مثيلًا جديدًا من الفئة `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` بلون محدد دقيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | اللون الدقيق الذي يُنشأ منه النطاق. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


يحصل على قيمة درجة اللون الابتدائية، بالدرجات.


**Returns:**
float - قيمة درجة اللون الابتدائية، بالدرجات.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


يضبط قيمة درجة اللون الابتدائية، بالدرجات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | float | قيمة درجة اللون الابتدائية، بالدرجات. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


يحصل على قيمة درجة اللون النهائية، بالدرجات.


**Returns:**
float - قيمة درجة اللون النهائية، بالدرجات.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


يضبط قيمة درجة اللون النهائية، بالدرجات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | float | قيمة درجة اللون النهائية، بالدرجات. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


يحصل على قيمة التشبع الابتدائية.


**Returns:**
float - يتراوح التشبع من 0.0 إلى 1.0، حيث 0.0 يعني تدرج الرمادي و1.0 هو أعلى تشبع.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


يضبط قيمة التشبع الابتدائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | float | يتراوح التشبع من 0.0 إلى 1.0، حيث 0.0 يعني تدرج الرمادي و1.0 هو أعلى تشبع. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


يحصل على قيمة التشبع النهائية.


**Returns:**
float - يتراوح التشبع من 0.0 إلى 1.0، حيث 0.0 يعني تدرج الرمادي و1.0 هو أعلى تشبع.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


يضبط قيمة التشبع النهائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | float | يتراوح التشبع من 0.0 إلى 1.0، حيث 0.0 يعني تدرج الرمادي و1.0 هو أعلى تشبع. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


يحصل على قيمة السطوع الابتدائية.


**Returns:**
float - يتراوح السطوع من 0.0 إلى 1.0، حيث 0.0 يمثل الأسود و1.0 يمثل الأبيض.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


يضبط قيمة السطوع الابتدائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | float | يتراوح السطوع من 0.0 إلى 1.0، حيث 0.0 يمثل الأسود و1.0 يمثل الأبيض. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


يحصل على قيمة السطوع النهائية.


**Returns:**
float - يتراوح السطوع من 0.0 إلى 1.0، حيث 0.0 يمثل الأسود و1.0 يمثل الأبيض.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


يضبط قيمة السطوع النهائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | float | يتراوح السطوع من 0.0 إلى 1.0، حيث 0.0 يمثل الأسود و1.0 يمثل الأبيض. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كان اللون الفارغ فقط ضمن النطاق.


**Returns:**
boolean - صحيح إذا كان اللون الفارغ فقط ضمن النطاق (يتم تجاهل نطاقات HSB)؛ وإلا، خطأ.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان اللون الفارغ فقط ضمن النطاق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | صحيح إذا كان اللون الفارغ فقط ضمن النطاق (يتم تجاهل نطاقات HSB)؛ وإلا، خطأ. |
|

