---
title: "OfficeImageFillFormat"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل إعدادات تنسيق تعبئة الصورة في أي محتوى Office مدعوم."
type: docs
weight: 46
url: /ar/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

يمثل إعدادات تنسيق تعبئة الصورة في أي محتوى Office مدعوم.


TWatermarkableImage
: النوع الدقيق للصورة القابلة للعلامة المائية المستخدمة كخلفية.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | يضبط قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية. |
|
|  | [getTransparency()](#getTransparency--) | يحصل على شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) إلى 1.0 (شفافة بالكامل). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | يضبط شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) إلى 1.0 (شفافة بالكامل). |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | يحصل على الصورة الخلفية. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | يضبط الصورة الخلفية. |
|
|  | [checkIfBackgroundImageIsSet()](#checkIfBackgroundImageIsSet--) | <br /> |

|
### OfficeImageFillFormat() {#OfficeImageFillFormat--}
```
public OfficeImageFillFormat()
```


<br />



### getTileAsTexture() {#getTileAsTexture--}
```
public abstract boolean getTileAsTexture()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية.


**Returns:**
منطقي - صحيح إذا كانت الصورة مكررة عبر الخلفية؛ وإلا، خطأ (الصورة ممتدة).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | صحيح إذا كانت الصورة مكررة عبر الخلفية؛ وإلا، خطأ (الصورة ممتدة). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


يحصل على شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) إلى 1.0 (شفافة بالكامل).


**Returns:**
مزدوج - شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) حتى 1.0 (شفافة بالكامل).

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


يضبط شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) إلى 1.0 (شفافة بالكامل).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) حتى 1.0 (شفافة بالكامل). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


يحصل على الصورة الخلفية.


**Returns:**
TWatermarkableImage - الصورة الخلفية. تُعيد null إذا لم يتم تعيين الصورة.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


يضبط الصورة الخلفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | TWatermarkableImage | الصورة الخلفية. تُعيد null إذا لم يتم تعيين الصورة. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



