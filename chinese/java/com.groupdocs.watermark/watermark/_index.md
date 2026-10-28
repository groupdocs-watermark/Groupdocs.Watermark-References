---
title: "水印"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示要添加到文档的水印。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

表示要添加到文档的水印。

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | 获取或设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的不透明度。 |
|
|  | [setOpacity(double value)](#setOpacity-double-) | 获取或设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的不透明度。 |
|
|  | [getY()](#getY--) | 获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 y 坐标。 |
|
|  | [setY(double value)](#setY-double-) | 设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 y 坐标。 |
|
|  | [getX()](#getX--) | 获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 x 坐标。 |
|
|  | [setX(double value)](#setX-double-) | 设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 x 坐标。 |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | 获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的垂直对齐方式。 |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的垂直对齐方式。 |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的水平对齐方式。 |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的水平对齐方式。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的旋转角度（以度为单位）。 |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的旋转角度（以度为单位）。 |
|
|  | [isBackground()](#isBackground--) | 获取一个值，指示是否应将水印放置在背景上。 |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | 设置一个值，指示是否应将水印放置在背景上。 |
|
|  | [getMargins()](#getMargins--) | 获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的边距设置。 |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | 设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的边距设置。 |
|
|  | [getPagesSetup()](#getPagesSetup--) | 获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的页面设置。 |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | 设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的页面设置。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望高度。 |
|
|  | [setHeight(double value)](#setHeight-double-) | 设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望高度。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望宽度。 |
|
|  | [setWidth(double value)](#setWidth-double-) | 设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望宽度。 |
|
|  | [getScaleFactor()](#getScaleFactor--) | 获取一个定义水印大小如何依赖于父级大小的值。 |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | 设置一个定义水印大小如何依赖于父级大小的值。 |
|
|  | [getSizingType()](#getSizingType--) | 获取一个指定水印应如何尺寸化的值。 |
|
|  | [setSizingType(int value)](#setSizingType-int-) | 设置一个指定水印应如何尺寸化的值。 |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | 获取一个指示是否计算水印大小和坐标的值 |
考虑父级边距。
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | 设置一个指示是否计算水印大小和坐标的值 |
考虑父级边距。
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getTransparency()](#getTransparency--) |  |
| [getSize()](#getSize--) |  |
| [getTileOptions()](#getTileOptions--) |  |
| [setTileOptions(TileOptions tileOptions)](#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-) |  |
| [copyPropertiesValues(Watermark source, Watermark destination)](#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```




### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


获取或设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的不透明度。

不透明度的值应在 0 到 1 之间。默认值为 1。


**Returns:**
double - 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的不透明度。

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


获取或设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的不透明度。

不透明度的值应在 0 到 1 之间。默认值为 1。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的不透明度。 |
|

### getY() {#getY--}
```
public final double getY()
```


获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 y 坐标。


**Returns:**
double - 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 y 坐标。

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 y 坐标。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 y 坐标。 |
|

### getX() {#getX--}
```
public final double getX()
```


获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 x 坐标。


**Returns:**
double - 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 x 坐标。

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 x 坐标。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 x 坐标。 |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的垂直对齐方式。

默认值是 `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`。


**Returns:**
int - 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)`。

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的垂直对齐方式。

默认值是 `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)`。 |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的水平对齐方式。

默认值是 `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`。


**Returns:**
int - 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)`。

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的水平对齐方式。

默认值是 `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的 `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)`。 |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的旋转角度（以度为单位）。


**Returns:**
double - 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的旋转角度（单位为度）。

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的旋转角度（以度为单位）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的旋转角度（单位为度）。 |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


获取一个值，指示是否应将水印放置在背景上。


**Returns:**
boolean - 如果值为 true，水印将放置在底部。默认情况下，值为 false，水印将放置在顶部。

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


设置一个值，指示是否应将水印放置在背景上。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果值为 true，水印将放置在底部。默认情况下，值为 false，水印将放置在顶部。 |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的边距设置。


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的边距设置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的边距设置。 |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的页面设置。


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的页面设置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的页面设置。 |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望高度。


**Returns:**
double - 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望高度。

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望高度。

设置此属性还会更改 `#getSizingType().getSizingType()` 的值。
属性设置为 `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望高度。 |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望宽度。


**Returns:**
double - 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望宽度。

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


设置此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望宽度。

设置此属性还会更改 `#getSizingType().getSizingType()` 的值。
属性设置为 `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的期望宽度。 |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


获取一个定义水印大小如何依赖于父级大小的值。

该值必须介于 0 和 1 之间。


**Returns:**
double - 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的缩放因子。

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


设置一个定义水印大小如何依赖于父级大小的值。

该值必须介于 0 和 1 之间。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[Watermark](../../com.groupdocs.watermark/watermark)` 的缩放因子。 |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


获取一个指定水印应如何尺寸化的值。


**Returns:**
int - 尺寸类型。

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


设置一个指定水印应如何尺寸化的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 尺寸类型。 |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


获取一个指示是否计算水印大小和坐标的值
考虑父级边距。


**Returns:**
boolean - 如果值为 true，水印的大小和坐标将在考虑父级边距的情况下计算。默认情况下，值为 false，父级边距将被忽略。

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


设置一个指示是否计算水印大小和坐标的值
考虑父级边距。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果值为 true，水印的大小和坐标将在考虑父级边距的情况下计算。默认情况下，值为 false，父级边距将被忽略。 |
|

### isImageWatermark() {#isImageWatermark--}
```
public abstract boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public abstract boolean isTextWatermark()
```




**Returns:**
boolean
### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getSize() {#getSize--}
```
public abstract SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getTileOptions() {#getTileOptions--}
```
public TileOptions getTileOptions()
```




**Returns:**
[TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions)
### setTileOptions(TileOptions tileOptions) {#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-}
```
public void setTileOptions(TileOptions tileOptions)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| destination | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### deepClone() {#deepClone--}
```
public abstract Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
