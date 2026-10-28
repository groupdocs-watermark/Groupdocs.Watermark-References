---
title: "SpreadsheetHeaderFooterPossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Excel 文档页眉或页脚中的可能水印。"
type: docs
weight: 62
url: /zh/java/com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class SpreadsheetHeaderFooterPossibleWatermark extends PossibleWatermark
```

表示 Excel 文档页眉或页脚中的可能水印。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section)](#SpreadsheetHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetHeaderFooterSection-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getParent()](#getParent--) | 获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的父对象。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的高度（以点为单位）。 |
|
|  | [getX()](#getX--) | 获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 相对于工作表左边界的水平偏移（以点为单位）。 |
|
|  | [getY()](#getY--) | 获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 相对于工作表顶部边界的垂直偏移（以点为单位）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的旋转角度（单位：度）。 |
|
|  | [getText()](#getText--) | 获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的文本。 |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。 |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section) {#SpreadsheetHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetHeaderFooterSection-}
```
public SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的父对象。


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的宽度（单位：点）。


**Returns:**
double - 此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的宽度（以点为单位）。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的高度（以点为单位）。


**Returns:**
double - 此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的高度（以点为单位）。

### getX() {#getX--}
```
public double getX()
```


获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 相对于工作表左边界的水平偏移（以点为单位）。


**Returns:**
double - 此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的 x 坐标。

### getY() {#getY--}
```
public double getY()
```


获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 相对于工作表顶部边界的垂直偏移（以点为单位）。


**Returns:**
double - 此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的 y 坐标。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的旋转角度（单位：度）。

### getText() {#getText--}
```
public String getText()
```


获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的文本。


**Returns:**
java.lang.String - 此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的文本。 |
|

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


获取此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。


**Returns:**
int - 此 `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。

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




