---
title: "AttachedImagePossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在任何受支持格式内容中的附加图像水印。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.watermark.search/attachedimagepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public abstract class AttachedImagePossibleWatermark<T> extends PossibleWatermark
```

表示在任何受支持格式内容中的附加图像水印。


T
: 附件的类型。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getParent()](#getParent--) | 获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的父对象。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的宽度。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的高度。 |
|
|  | [getX()](#getX--) | 获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的 x 坐标。 |
|
|  | [getY()](#getY--) | 获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的 y 坐标。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的旋转角度（单位：度）。 |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的测量单位 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。 |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getParent() {#getParent--}
```
public ContentPart getParent()
```


获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的父对象。


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的宽度。


**Returns:**
double - 此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的宽度。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的高度。


**Returns:**
double - 此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的高度。

### getX() {#getX--}
```
public double getX()
```


获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的 x 坐标。


**Returns:**
double - 此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的 x 坐标。

### getY() {#getY--}
```
public double getY()
```


获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的 y 坐标。


**Returns:**
double - 此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的 y 坐标。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的旋转角度。

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


获取此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的测量单位 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。


**Returns:**
int - 此 `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` 的测量单位 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。

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




