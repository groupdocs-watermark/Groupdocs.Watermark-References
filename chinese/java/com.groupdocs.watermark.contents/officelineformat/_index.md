---
title: "OfficeLineFormat"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示形状线条格式。"
type: docs
weight: 47
url: /zh/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

表示形状线条格式。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | 初始化 `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWeight()](#getWeight--) | 获取用于描绘形状路径的笔刷粗细。 |
|
|  | [setWeight(double value)](#setWeight-double-) | 设置用于描绘形状路径的笔刷粗细。 |
|
|  | [getColor()](#getColor--) | 获取线条的颜色。 |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | 设置线条的颜色。 |
|
|  | [getOpacity()](#getOpacity--) | 获取线条的不透明度。 |
|
|  | [setOpacity(double value)](#setOpacity-double-) | 设置线条的不透明度。 |
|
|  | [getEnabled()](#getEnabled--) | 获取指示形状是否将被描边的值。 |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | 设置指示形状是否将被描边的值。 |
|
|  | [getDashStyle()](#getDashStyle--) | 获取线条的点划线模式。 |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | 设置线条的点划线模式。 |
|
|  | [getLineStyle()](#getLineStyle--) | 获取线条样式。 |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | 设置线条样式。 |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


初始化 `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` 类的新实例。


### getWeight() {#getWeight--}
```
public final double getWeight()
```


获取用于描绘形状路径的笔刷粗细。


**Returns:**
double - 线条粗细（以点为单位）。默认值为 0.75。

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


设置用于描绘形状路径的笔刷粗细。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 线条粗细（以点为单位）。默认值为 0.75。 |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


获取线条的颜色。

默认值为 `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`。


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


设置线条的颜色。

默认值为 `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | 线条的颜色。 |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


获取线条的不透明度。


**Returns:**
double - 该值应在 0 到 1 之间。默认值为 1。

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


设置线条的不透明度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 该值应在 0 到 1 之间。默认值为 1。 |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


获取指示形状是否将被描边的值。


**Returns:**
boolean - 默认值为 false。

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


设置指示形状是否将被描边的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 默认值为 false。 |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


获取线条的点划线模式。

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


设置线条的点划线模式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


获取线条样式。

默认值为 `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`。


**Returns:**
int - 线条样式。

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


设置线条样式。

默认值为 `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 线条样式。 |
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
