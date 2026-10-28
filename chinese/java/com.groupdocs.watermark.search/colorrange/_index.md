---
title: "ColorRange"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示一系列颜色。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

表示一系列颜色。使用 RGB 颜色的 HSB 表示来指定范围。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | 初始化 `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` 类的新实例。 |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | 使用指定的精确颜色初始化 `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | 获取起始色相值（单位为度）。 |
|
|  | [setMinHue(float value)](#setMinHue-float-) | 设置起始色相值（单位为度）。 |
|
|  | [getMaxHue()](#getMaxHue--) | 获取结束色相值（单位为度）。 |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | 设置结束色相值（单位为度）。 |
|
|  | [getMinSaturation()](#getMinSaturation--) | 获取起始饱和度值。 |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | 设置起始饱和度值。 |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | 获取结束饱和度值。 |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | 设置结束饱和度值。 |
|
|  | [getMinBrightness()](#getMinBrightness--) | 获取起始亮度值。 |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | 设置起始亮度值。 |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | 获取结束亮度值。 |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | 设置结束亮度值。 |
|
|  | [isEmpty()](#isEmpty--) | 获取一个值，指示是否仅空颜色在范围内。 |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | 设置一个值，指示是否仅空颜色在范围内。 |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


初始化 `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` 类的新实例。


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


使用指定的精确颜色初始化 `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 创建范围的精确颜色。 |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


获取起始色相值（单位为度）。


**Returns:**
float - 起始色相值（以度为单位）。

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


设置起始色相值（单位为度）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 起始色相值（以度为单位）。 |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


获取结束色相值（单位为度）。


**Returns:**
float - 结束色相值（以度为单位）。

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


设置结束色相值（单位为度）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 结束色相值（以度为单位）。 |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


获取起始饱和度值。


**Returns:**
float - 饱和度范围为 0.0 到 1.0，其中 0.0 为灰度，1.0 为最高饱和度。

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


设置起始饱和度值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 饱和度范围为 0.0 到 1.0，其中 0.0 为灰度，1.0 为最高饱和度。 |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


获取结束饱和度值。


**Returns:**
float - 饱和度范围为 0.0 到 1.0，其中 0.0 为灰度，1.0 为最高饱和度。

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


设置结束饱和度值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 饱和度范围为 0.0 到 1.0，其中 0.0 为灰度，1.0 为最高饱和度。 |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


获取起始亮度值。


**Returns:**
float - 亮度范围为 0.0 到 1.0，其中 0.0 表示黑色，1.0 表示白色。

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


设置起始亮度值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 亮度范围为 0.0 到 1.0，其中 0.0 表示黑色，1.0 表示白色。 |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


获取结束亮度值。


**Returns:**
float - 亮度范围为 0.0 到 1.0，其中 0.0 表示黑色，1.0 表示白色。

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


设置结束亮度值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 亮度范围为 0.0 到 1.0，其中 0.0 表示黑色，1.0 表示白色。 |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


获取一个值，指示是否仅空颜色在范围内。


**Returns:**
boolean - 如果仅空颜色在范围内（HSB 范围被忽略），则为 true；否则为 false。

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


设置一个值，指示是否仅空颜色在范围内。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果仅空颜色在范围内（HSB 范围被忽略），则为 true；否则为 false。 |
|

