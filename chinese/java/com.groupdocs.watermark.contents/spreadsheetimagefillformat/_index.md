---
title: "SpreadsheetImageFillFormat"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Excel 文档中图像填充格式设置。"
type: docs
weight: 114
url: /zh/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

表示 Excel 文档中图像填充格式设置。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | 获取一个值，指示图像是否在背景上平铺。 |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | 设置一个值，指示图像是否在背景上平铺。 |
|
|  | [getTransparency()](#getTransparency--) | 获取背景图像的透明度，取值范围从 0.0（不透明） |
到 1.0（完全透明）。
|
|  | [setTransparency(double value)](#setTransparency-double-) | 设置背景图像的透明度，取值范围从 0.0（不透明） |
到 1.0（完全透明）。
|
|  | [getBackgroundImage()](#getBackgroundImage--) | 获取背景图像。 |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | 设置背景图像。 |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


获取一个值，指示图像是否在背景上平铺。


**Returns:**
boolean - 如果图像在背景上平铺则为 True；否则为 false（图像被拉伸）。

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


设置一个值，指示图像是否在背景上平铺。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果图像在背景上平铺则为 True；否则为 false（图像被拉伸）。 |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


获取背景图像的透明度，取值范围从 0.0（不透明）
到 1.0（完全透明）。


**Returns:**
double - 背景图像的透明度，取值范围从 0.0（不透明）到 1.0（完全透明）。

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


设置背景图像的透明度，取值范围从 0.0（不透明）
到 1.0（完全透明）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 背景图像的透明度，取值范围从 0.0（不透明）到 1.0（完全透明）。 |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


获取背景图像。


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


设置背景图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | 背景图像。如果未设置图像，则返回 null。 |
|

