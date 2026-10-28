---
title: "HyperlinkPossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PowerPoint 内容中可能的超链接水印。"
type: docs
weight: 29
url: /zh/java/com.groupdocs.watermark.search/hyperlinkpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class HyperlinkPossibleWatermark extends PossibleWatermark
```

表示 PowerPoint 内容中可能的超链接水印。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HyperlinkPossibleWatermark(PossibleWatermark parentWatermark, IHyperlinkContainer hyperlinkContainer)](#HyperlinkPossibleWatermark-com.groupdocs.watermark.search.PossibleWatermark-com.groupdocs.watermark.search.IHyperlinkContainer-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getParent()](#getParent--) | 获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的父对象。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的宽度。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的高度。 |
|
|  | [getX()](#getX--) | 获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 x 坐标。 |
|
|  | [getY()](#getY--) | 获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 y 坐标。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的旋转角度（单位：度）。 |
|
|  | [getText()](#getText--) | 获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 URL。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 URL。 |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` 单位。 |
|
| [remove()](#remove--) |  |
### HyperlinkPossibleWatermark(PossibleWatermark parentWatermark, IHyperlinkContainer hyperlinkContainer) {#HyperlinkPossibleWatermark-com.groupdocs.watermark.search.PossibleWatermark-com.groupdocs.watermark.search.IHyperlinkContainer-}
```
public HyperlinkPossibleWatermark(PossibleWatermark parentWatermark, IHyperlinkContainer hyperlinkContainer)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parentWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |
| hyperlinkContainer | [IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的父对象。


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的宽度。


**Returns:**
double - 此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的宽度。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的高度。


**Returns:**
double - 此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的高度。

### getX() {#getX--}
```
public double getX()
```


获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 x 坐标。


**Returns:**
double - 此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 x 坐标。

### getY() {#getY--}
```
public double getY()
```


获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 y 坐标。


**Returns:**
double - 此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 y 坐标。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的旋转角度。

### getText() {#getText--}
```
public String getText()
```


获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 URL。


**Returns:**
java.lang.String - 此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 URL。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 URL。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 URL。 |
|

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


获取此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` 单位。


**Returns:**
int - 此 `[HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` 单位。

### remove() {#remove--}
```
public void remove()
```




