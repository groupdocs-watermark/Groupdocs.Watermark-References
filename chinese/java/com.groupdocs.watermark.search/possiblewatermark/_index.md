---
title: "PossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在文档中发现的可能水印。"
type: docs
weight: 45
url: /zh/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

表示在文档中发现的可能水印。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getParent()](#getParent--) | 获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的父对象。 |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | 获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的宽度。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的高度。 |
|
|  | [getX()](#getX--) | 获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的 x 坐标。 |
|
|  | [getY()](#getY--) | 获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的 y 坐标。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的旋转角度（单位：度）。 |
|
|  | [getText()](#getText--) | 获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的文本。 |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的格式化文本片段集合。 |
|
|  | [getImageData()](#getImageData--) | 获取或设置此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的图像。 |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的测量单位 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。 |
|
| [getCollection()](#getCollection--) |  |
| [setCollection(PossibleWatermarkCollection value)](#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-) |  |
| [getImageSize()](#getImageSize--) |  |
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PossibleWatermark() {#PossibleWatermark--}
```
public PossibleWatermark()
```




### getParent() {#getParent--}
```
public abstract ContentPart getParent()
```


获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的父对象。


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的宽度。


**Returns:**
double - 此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的宽度。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的高度。


**Returns:**
double - 此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的高度。

### getX() {#getX--}
```
public double getX()
```


获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的 x 坐标。


**Returns:**
double - 此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的 x 坐标。

### getY() {#getY--}
```
public double getY()
```


获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的 y 坐标。


**Returns:**
double - 此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的 y 坐标。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的旋转角度。

### getText() {#getText--}
```
public String getText()
```


获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的文本。


**Returns:**
java.lang.String - 此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的文本。 |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的格式化文本片段集合。


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


获取或设置此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的图像。


**Returns:**
byte[] - 此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的图像，若水印没有图像则为 null。

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


获取此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的测量单位 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。


**Returns:**
int - 此 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` 的测量单位 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。

### getCollection() {#getCollection--}
```
public final PossibleWatermarkCollection getCollection()
```




**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### setCollection(PossibleWatermarkCollection value) {#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void setCollection(PossibleWatermarkCollection value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```




**Returns:**
[Size](../../com.groupdocs.watermark.internal/size)
### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public abstract void remove()
```




