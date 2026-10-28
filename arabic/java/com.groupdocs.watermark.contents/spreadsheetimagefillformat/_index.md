---
title: "SpreadsheetImageFillFormat"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل إعدادات تنسيق تعبئة الصورة في مستند Excel."
type: docs
weight: 114
url: /ar/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

يمثل إعدادات تنسيق تعبئة الصورة في مستند Excel.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | يضبط قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية. |
|
|  | [getTransparency()](#getTransparency--) | يحصل على شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) |
حتى 1.0 (شفافة بالكامل).
|
|  | [setTransparency(double value)](#setTransparency-double-) | يضبط شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) |
حتى 1.0 (شفافة بالكامل).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | يحصل على الصورة الخلفية. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | يضبط الصورة الخلفية. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية.


**Returns:**
منطقي - صحيح إذا كانت الصورة مكررة عبر الخلفية؛ وإلا، خطأ (الصورة ممتدة).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | صحيح إذا كانت الصورة مكررة عبر الخلفية؛ وإلا، خطأ (الصورة ممتدة). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


يحصل على شفافية الصورة الخلفية كقيمة من 0.0 (معتمة)
حتى 1.0 (شفافة بالكامل).


**Returns:**
مزدوج - شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) حتى 1.0 (شفافة بالكامل).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


يضبط شفافية الصورة الخلفية كقيمة من 0.0 (معتمة)
حتى 1.0 (شفافة بالكامل).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) حتى 1.0 (شفافة بالكامل). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


يحصل على الصورة الخلفية.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


يضبط الصورة الخلفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | الصورة الخلفية. تُعيد null إذا لم يتم تعيين الصورة. |
|

