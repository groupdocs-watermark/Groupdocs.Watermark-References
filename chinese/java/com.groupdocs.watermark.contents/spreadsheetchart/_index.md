---
title: "SpreadsheetChart"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Excel 文档中的图表。"
type: docs
weight: 106
url: /zh/java/com.groupdocs.watermark.contents/spreadsheetchart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer), [com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetChart implements IHyperlinkContainer, ITwoDObject
```

表示 Excel 文档中的图表。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | 获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的父工作表。 |
|
|  | [getId()](#getId--) | 获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的标识符。 |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | 获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的图像填充格式设置。 |
|
|  | [getName()](#getName--) | 获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的名称。 |
|
|  | [getAlternativeText()](#getAlternativeText--) | 获取与此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 关联的描述性（替代）文本。 |
|
|  | [getHyperlink()](#getHyperlink--) | 获取与此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 关联的超链接。 |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | 设置与此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 关联的超链接。 |
|
|  | [getX()](#getX--) | 获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 相对于工作表左边界的水平偏移（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 相对于工作表上边界的垂直偏移（单位：点）。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的高度（单位：点）。 |
|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的父工作表。


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getId() {#getId--}
```
public final int getId()
```


获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的标识符。


**Returns:**
int - 此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的标识符。

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的图像填充格式设置。


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getName() {#getName--}
```
public final String getName()
```


获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的名称。


**Returns:**
java.lang.String - 此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的名称。

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


获取与此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 关联的描述性（替代）文本。


**Returns:**
java.lang.String - 与此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 关联的描述性（替代）文本。

### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


获取与此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 关联的超链接。


**Returns:**
java.lang.String - 与此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 关联的超链接。

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


设置与此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 关联的超链接。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 与此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 关联的超链接。 |
|

### getX() {#getX--}
```
public final double getX()
```


获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 相对于工作表左边界的水平偏移（单位：点）。


**Returns:**
double - 此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的 X 坐标。

### getY() {#getY--}
```
public final double getY()
```


获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 相对于工作表上边界的垂直偏移（单位：点）。


**Returns:**
double - 此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的 Y 坐标。

### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的宽度（单位：点）。


**Returns:**
double - 此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的宽度（以点为单位）。

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的高度（单位：点）。


**Returns:**
double - 此 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` 的高度（以点为单位）。

