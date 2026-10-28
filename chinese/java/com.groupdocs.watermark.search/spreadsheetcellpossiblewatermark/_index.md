---
title: "SpreadsheetCellPossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Excel 文档中的可能单元格水印。"
type: docs
weight: 60
url: /zh/java/com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class SpreadsheetCellPossibleWatermark extends PossibleWatermark
```

表示 Excel 文档中的可能单元格水印。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SpreadsheetCellPossibleWatermark(Cell cell, SpreadsheetWorksheet parent)](#SpreadsheetCellPossibleWatermark-com.aspose.cells.Cell-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getParent()](#getParent--) | 获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的父对象。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的高度（单位：点）。 |
|
|  | [getX()](#getX--) | 获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 相对于内容左边界的水平偏移量（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 相对于内容上边界的垂直偏移量（单位：点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的旋转角度（单位：度）。 |
|
|  | [getText()](#getText--) | 获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的文本。 |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的格式化文本片段集合。 |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。 |
|
| [remove()](#remove--) |  |
### SpreadsheetCellPossibleWatermark(Cell cell, SpreadsheetWorksheet parent) {#SpreadsheetCellPossibleWatermark-com.aspose.cells.Cell-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetCellPossibleWatermark(Cell cell, SpreadsheetWorksheet parent)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 单元格 | com.aspose.cells.Cell |  |
| parent | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的父对象。


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的宽度（单位：点）。


**Returns:**
double - 此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的宽度（单位：点）。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的高度（单位：点）。


**Returns:**
double - 此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的高度（单位：点）。

### getX() {#getX--}
```
public double getX()
```


获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 相对于内容左边界的水平偏移量（单位：点）。


**Returns:**
double - 此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的 X 坐标。

### getY() {#getY--}
```
public double getY()
```


获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 相对于内容上边界的垂直偏移量（单位：点）。


**Returns:**
double - 此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的 Y 坐标。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的旋转角度（单位：度）。

### getText() {#getText--}
```
public String getText()
```


获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的文本。


**Returns:**
java.lang.String - 此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的文本。 |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的格式化文本片段集合。


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


获取此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。


**Returns:**
int - 此 `[SpreadsheetCellPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetcellpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。

### remove() {#remove--}
```
public void remove()
```




