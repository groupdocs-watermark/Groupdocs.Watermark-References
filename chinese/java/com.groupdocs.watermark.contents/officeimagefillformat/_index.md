---
title: "OfficeImageFillFormat"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示任何受支持的办公内容中的图像填充格式设置。"
type: docs
weight: 46
url: /zh/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

表示任何受支持的办公内容中的图像填充格式设置。


TWatermarkableImage
: 用作背景的可水印图像的确切类型。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | 获取一个值，指示图像是否在背景上平铺。 |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | 设置一个值，指示图像是否在背景上平铺。 |
|
|  | [getTransparency()](#getTransparency--) | 获取背景图像的透明度，取值范围为 0.0（不透明）至 1.0（完全透明）。 |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 设置背景图像的透明度，取值范围为 0.0（不透明）至 1.0（完全透明）。 |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | 获取背景图像。 |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | 设置背景图像。 |
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


获取一个值，指示图像是否在背景上平铺。


**Returns:**
boolean - 如果图像在背景上平铺则为 True；否则为 false（图像被拉伸）。

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


设置一个值，指示图像是否在背景上平铺。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果图像在背景上平铺则为 True；否则为 false（图像被拉伸）。 |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


获取背景图像的透明度，取值范围为 0.0（不透明）至 1.0（完全透明）。


**Returns:**
double - 背景图像的透明度，取值范围从 0.0（不透明）到 1.0（完全透明）。

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


设置背景图像的透明度，取值范围为 0.0（不透明）至 1.0（完全透明）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 背景图像的透明度，取值范围从 0.0（不透明）到 1.0（完全透明）。 |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


获取背景图像。


**Returns:**
TWatermarkableImage - 背景图像。如果未设置图像，则返回 null。

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


设置背景图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | TWatermarkableImage | 背景图像。如果未设置图像，则返回 null。 |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



