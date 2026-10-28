---
title: "DiagramHeaderFooterPossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Visio 文档页眉/页脚中可能的水印。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class DiagramHeaderFooterPossibleWatermark extends PossibleWatermark
```

表示 Visio 文档页眉/页脚中可能的水印。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DiagramHeaderFooterPossibleWatermark(DiagramContent content, int headerFooterType)](#DiagramHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.DiagramContent-int-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getParent()](#getParent--) | 获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的父对象。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的高度（单位：点）。 |
|
|  | [getX()](#getX--) | 获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 相对于页面左边界的水平偏移（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 相对于页面底部边界的垂直偏移（单位：点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的旋转角度（单位：度）。 |
|
|  | [getText()](#getText--) | 获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的文本。 |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。 |
|
| [remove()](#remove--) |  |
### DiagramHeaderFooterPossibleWatermark(DiagramContent content, int headerFooterType) {#DiagramHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.DiagramContent-int-}
```
public DiagramHeaderFooterPossibleWatermark(DiagramContent content, int headerFooterType)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | [DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent) |  |
| headerFooterType | int |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的父对象。


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的宽度（单位：点）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的高度（单位：点）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getX() {#getX--}
```
public double getX()
```


获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 相对于页面左边界的水平偏移（单位：点）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getY() {#getY--}
```
public double getY()
```


获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 相对于页面底部边界的垂直偏移（单位：点）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的旋转角度（单位：度）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getText() {#getText--}
```
public String getText()
```


获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的文本。


**Returns:**
java.lang.String - 此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的文本。 |
|

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


获取此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。


**Returns:**
int - 此 `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。

### remove() {#remove--}
```
public void remove()
```




