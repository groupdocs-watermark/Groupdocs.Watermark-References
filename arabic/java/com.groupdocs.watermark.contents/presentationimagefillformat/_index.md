---
title: "PresentationImageFillFormat"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل إعدادات تنسيق تعبئة الصورة في مستند PowerPoint."
type: docs
weight: 85
url: /ar/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

يمثل إعدادات تنسيق تعبئة الصورة في مستند PowerPoint.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | يضبط قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية. |
|
|  | [getTransparency()](#getTransparency--) | يحصل على شفافية الصورة الخلفية كقيمة من 0.0 (معتم) إلى 1.0 |
(شفافة تمامًا).
|
|  | [setTransparency(double value)](#setTransparency-double-) | يضبط شفافية الصورة الخلفية كقيمة من 0.0 (معتم) إلى 1.0 |
(شفافة تمامًا).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | يحصل على الصورة الخلفية. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | يضبط الصورة الخلفية. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية.


**Returns:**
boolean - True إذا كانت الصورة مكررة عبر الخلفية؛ وإلا false (الصورة مُمددة). القيمة الافتراضية هي false.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت الصورة مكررة عبر الخلفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | True إذا كانت الصورة مكررة عبر الخلفية؛ وإلا false (الصورة مُمددة). القيمة الافتراضية هي false. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


يحصل على شفافية الصورة الخلفية كقيمة من 0.0 (معتم) إلى 1.0
(شفافة تمامًا).


**Returns:**
مزدوج - شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) حتى 1.0 (شفافة بالكامل).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


يضبط شفافية الصورة الخلفية كقيمة من 0.0 (معتم) إلى 1.0
(شفافة تمامًا).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | شفافية الصورة الخلفية كقيمة من 0.0 (معتمة) حتى 1.0 (شفافة بالكامل). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


يحصل على الصورة الخلفية.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


يضبط الصورة الخلفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | الصورة الخلفية. تُعيد null إذا لم يتم تعيين الصورة. |
|

