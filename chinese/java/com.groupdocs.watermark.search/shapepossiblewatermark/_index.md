---
title: "ShapePossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示任何受支持格式内容中的形状水印。"
type: docs
weight: 55
url: /zh/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

表示任何受支持格式内容中的形状水印。


T
: 形状的类型。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | 获取 形状的旋转角度（单位：度）。 |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 获取 形状的格式化文本片段集合。 |
|
|  | [getText()](#getText--) | 获取 形状的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置 形状的文本。 |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取 形状的旋转角度（单位：度）。


**Returns:**
double - 形状的旋转角度（单位：度）。

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


获取 形状的格式化文本片段集合。


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


获取 形状的文本。


**Returns:**
java.lang.String - 形状的文本。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置 形状的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 形状的文本。 |
|

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




