---
title: "Margins"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示对象每个边缘的边距设置。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

表示对象每个边缘的边距设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Margins()](#Margins--) | 初始化 `[Margins](../../com.groupdocs.watermark.watermarks/margins)` 类的新实例。 |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | 使用指定的类型、位置和大小初始化 `[Margins](../../com.groupdocs.watermark.watermarks/margins)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | 获取 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`。 |
|
|  | [setMarginType(int value)](#setMarginType-int-) | 设置 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`。 |
|
|  | [getLeft()](#getLeft--) | 获取左边距。 |
|
|  | [setLeft(double value)](#setLeft-double-) | 设置左边距。 |
|
|  | [getRight()](#getRight--) | 获取右边距。 |
|
|  | [setRight(double value)](#setRight-double-) | 设置右边距。 |
|
|  | [getTop()](#getTop--) | 获取上边距。 |
|
|  | [setTop(double value)](#setTop-double-) | 设置上边距。 |
|
|  | [getBottom()](#getBottom--) | 获取下边距。 |
|
|  | [setBottom(double value)](#setBottom-double-) | 设置下边距。 |
|
### Margins() {#Margins--}
```
public Margins()
```


初始化 `[Margins](../../com.groupdocs.watermark.watermarks/margins)` 类的新实例。


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


使用指定的类型、位置和大小初始化 `[Margins](../../com.groupdocs.watermark.watermarks/margins)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | marginType | int | 此 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`。指定应如何解释边距值。 |
|
|  | 左 | double | 左边距的值。 |
|
|  | 右 | double | 右边距的值。 |
|
|  | 上 | double | 上边距的值。 |
|
|  | 下 | double | 下边距的值。 |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


获取 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`。将新值设置到此属性会自动将所有边距恢复为默认值（零）。

默认值是 `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - 指定应如何解释边距的值。

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


设置 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`。将新值设置到此属性会自动将所有边距恢复为默认值（零）。

默认值是 `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 指定应如何解释边距的值。 |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


获取左边距。


**Returns:**
double - 相对于父级左边框的水平偏移。

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


设置左边距。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 相对于父级左边框的水平偏移。 |
|

### getRight() {#getRight--}
```
public final double getRight()
```


获取右边距。


**Returns:**
double - 相对于父级右边框的水平偏移。

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


设置右边距。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 相对于父级右边框的水平偏移。 |
|

### getTop() {#getTop--}
```
public final double getTop()
```


获取上边距。


**Returns:**
double - 相对于父级上边框的水平偏移。

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


设置上边距。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 相对于父级上边框的水平偏移。 |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


获取下边距。


**Returns:**
double - 相对于父级下边框的水平偏移。

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


设置下边距。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 相对于父级下边框的水平偏移。 |
|

