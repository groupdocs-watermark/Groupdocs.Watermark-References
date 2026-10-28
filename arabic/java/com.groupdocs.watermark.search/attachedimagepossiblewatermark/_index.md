---
title: "AttachedImagePossibleWatermark"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل علامة مائية صورة مرفقة في محتوى أي صيغة مدعومة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.watermark.search/attachedimagepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public abstract class AttachedImagePossibleWatermark<T> extends PossibleWatermark
```

يمثل علامة مائية صورة مرفقة في محتوى أي صيغة مدعومة.


T
: نوع المرفق.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getParent()](#getParent--) | يحصل على الأصل لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض هذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع هذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getX()](#getX--) | يحصل على إحداثي x لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getY()](#getY--) | يحصل على إحداثي y لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | يحصل على زاوية الدوران لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` بالدرجات. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | يحصل على وحدة القياس `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getParent() {#getParent--}
```
public ContentPart getParent()
```


يحصل على الأصل لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


يحصل على عرض هذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - عرض هذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


يحصل على ارتفاع هذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - ارتفاع هذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


يحصل على إحداثي x لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - إحداثي x لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


يحصل على إحداثي y لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - إحداثي y لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


يحصل على زاوية الدوران لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` بالدرجات.


**Returns:**
double - زاوية الدوران لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


يحصل على وحدة القياس `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
int - وحدة القياس `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` لهذا `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




