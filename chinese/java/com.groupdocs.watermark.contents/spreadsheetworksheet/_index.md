---
title: "SpreadsheetWorksheet"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Excel 文档工作表。"
type: docs
weight: 124
url: /zh/java/com.groupdocs.watermark.contents/spreadsheetworksheet/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class SpreadsheetWorksheet extends ContentPart
```

表示 Excel 文档工作表。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSpreadsheetDataSizeInPoints()](#getSpreadsheetDataSizeInPoints--) |  |
|  | [getPageSetup()](#getPageSetup--) | 获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的打印页面设置。 |
|
|  | [getContentAreaWidth()](#getContentAreaWidth--) | 获取内容区域的宽度（单位：点）。 |
|
|  | [getContentAreaWidthPx()](#getContentAreaWidthPx--) | 获取内容区域的宽度（单位：像素）。 |
|
|  | [getContentAreaHeight()](#getContentAreaHeight--) | 获取内容区域的高度（单位：点）。 |
|
|  | [getContentAreaHeightPx()](#getContentAreaHeightPx--) | 获取内容区域的高度（单位：像素）。 |
|
|  | [getShapes()](#getShapes--) | 获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的所有形状集合。 |
|
|  | [getAttachments()](#getAttachments--) | 获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的所有附件集合。 |
|
|  | [getCharts()](#getCharts--) | 获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的所有图表集合。 |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | 获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的背景图像。 |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | 设置此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的背景图像。 |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | 获取工作表页眉和页脚的集合。 |
|
|  | [getAsposeCellsWorksheet()](#getAsposeCellsWorksheet--) | <br /> |

|
|  | [getColumnWidth(int column)](#getColumnWidth-int-) | 获取指定列的宽度（单位：点）。 |
|
|  | [getColumnWidthPx(int column)](#getColumnWidthPx-int-) | 获取指定列的宽度（单位：像素）。 |
|
|  | [getRowHeight(int row)](#getRowHeight-int-) | 获取指定行的高度（单位：点）。 |
|
|  | [getRowHeightPx(int row)](#getRowHeightPx-int-) | 获取指定行的高度（单位：像素）。 |
|
|  | [addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | <br /> |

|
|  | [addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight)](#addWatermarkAsBackground-com.groupdocs.watermark.Watermark-int-int-) | <br /> |

|
|  | [addWatermarkIntoHeaderFooter(Watermark watermark)](#addWatermarkIntoHeaderFooter-com.groupdocs.watermark.Watermark-) | <br /> |

|
|  | [addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)](#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-) | <br /> |

|
|  | [addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)](#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | <br /> |

|
|  | [getRowY(int rowIndex)](#getRowY-int-) | <br /> |

|
|  | [getColumnX(int columnIndex)](#getColumnX-int-) | <br /> |

|
|  | [getRowRangeHeight(int startRow, int endRow)](#getRowRangeHeight-int-int-) | <br /> |

|
|  | [getColumnRangeWidth(int startColumn, int endColumn)](#getColumnRangeWidth-int-int-) | <br /> |

|
|  | [resetBackgroundImageReference()](#resetBackgroundImageReference--) | <br /> |

|
### getSpreadsheetDataSizeInPoints() {#getSpreadsheetDataSizeInPoints--}
```
public Size getSpreadsheetDataSizeInPoints()
```




**Returns:**
[Size](../../com.groupdocs.watermark.internal/size)
### getPageSetup() {#getPageSetup--}
```
public final SpreadsheetPageSetup getPageSetup()
```


获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的打印页面设置。


**Returns:**
[SpreadsheetPageSetup](../../com.groupdocs.watermark.contents/spreadsheetpagesetup) - The printing page setup for this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getContentAreaWidth() {#getContentAreaWidth--}
```
public final double getContentAreaWidth()
```


获取内容区域的宽度（单位：点）。


**Returns:**
double - 内容区域的宽度（单位：点）。

### getContentAreaWidthPx() {#getContentAreaWidthPx--}
```
public final int getContentAreaWidthPx()
```


获取内容区域的宽度（单位：像素）。


**Returns:**
int - 内容区域的宽度（单位：像素）。

### getContentAreaHeight() {#getContentAreaHeight--}
```
public final double getContentAreaHeight()
```


获取内容区域的高度（单位：点）。


**Returns:**
double - 内容区域的高度（单位：点）。

### getContentAreaHeightPx() {#getContentAreaHeightPx--}
```
public final int getContentAreaHeightPx()
```


获取内容区域的高度（单位：像素）。


**Returns:**
int - 内容区域的高度（单位：像素）。

### getShapes() {#getShapes--}
```
public final SpreadsheetShapeCollection getShapes()
```


获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的所有形状集合。


**Returns:**
[SpreadsheetShapeCollection](../../com.groupdocs.watermark.contents/spreadsheetshapecollection) - The collection of all shapes of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getAttachments() {#getAttachments--}
```
public final SpreadsheetAttachmentCollection getAttachments()
```


获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的所有附件集合。


**Returns:**
[SpreadsheetAttachmentCollection](../../com.groupdocs.watermark.contents/spreadsheetattachmentcollection) - The collection of all attachments of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getCharts() {#getCharts--}
```
public final SpreadsheetChartCollection getCharts()
```


获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的所有图表集合。


**Returns:**
[SpreadsheetChartCollection](../../com.groupdocs.watermark.contents/spreadsheetchartcollection) - The collection of all charts of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getBackgroundImage() {#getBackgroundImage--}
```
public final SpreadsheetWatermarkableImage getBackgroundImage()
```


获取此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的背景图像。


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` or `null` if the worksheet has no background image.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


设置此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的背景图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | 此 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 的背景图像，若要移除背景图像则为 `null`。 |
|

### getHeadersFooters() {#getHeadersFooters--}
```
public final SpreadsheetHeaderFooterCollection getHeadersFooters()
```


获取工作表页眉和页脚的集合。


**Returns:**
[SpreadsheetHeaderFooterCollection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootercollection) - The collection of headers and footers.

### getAsposeCellsWorksheet() {#getAsposeCellsWorksheet--}
```
public final Worksheet getAsposeCellsWorksheet()
```


<br />



**Returns:**
com.aspose.cells.Worksheet
### getColumnWidth(int column) {#getColumnWidth-int-}
```
public final double getColumnWidth(int column)
```


获取指定列的宽度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 列 | int | 列索引。 |
|

**Returns:**
double - 列的宽度（单位：点）。

### getColumnWidthPx(int column) {#getColumnWidthPx-int-}
```
public final int getColumnWidthPx(int column)
```


获取指定列的宽度（单位：像素）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 列 | int | 列索引。 |
|

**Returns:**
int - 列的宽度（单位：像素）。

### getRowHeight(int row) {#getRowHeight-int-}
```
public final double getRowHeight(int row)
```


获取指定行的高度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 行 | int | 行索引。 |
|

**Returns:**
double - 行的高度（单位：点）。

### getRowHeightPx(int row) {#getRowHeightPx-int-}
```
public final int getRowHeightPx(int row)
```


获取指定行的高度（单位：像素）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 行 | int | 行索引。 |
|

**Returns:**
int - 行的高度（单位：像素）。

### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |
| effects | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) |  |

### addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight) {#addWatermarkAsBackground-com.groupdocs.watermark.Watermark-int-int-}
```
public final void addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| backgroundWidth | int |  |
| backgroundHeight | int |  |

### addWatermarkIntoHeaderFooter(Watermark watermark) {#addWatermarkIntoHeaderFooter-com.groupdocs.watermark.Watermark-}
```
public final void addWatermarkIntoHeaderFooter(Watermark watermark)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |
| effects | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) |  |

### getRowY(int rowIndex) {#getRowY-int-}
```
public final double getRowY(int rowIndex)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | int |  |

**Returns:**
double
### getColumnX(int columnIndex) {#getColumnX-int-}
```
public final double getColumnX(int columnIndex)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int |  |

**Returns:**
double
### getRowRangeHeight(int startRow, int endRow) {#getRowRangeHeight-int-int-}
```
public final double getRowRangeHeight(int startRow, int endRow)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startRow | int |  |
| endRow | int |  |

**Returns:**
double
### getColumnRangeWidth(int startColumn, int endColumn) {#getColumnRangeWidth-int-int-}
```
public final double getColumnRangeWidth(int startColumn, int endColumn)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startColumn | int |  |
| endColumn | int |  |

**Returns:**
double
### resetBackgroundImageReference() {#resetBackgroundImageReference--}
```
public final void resetBackgroundImageReference()
```


<br />



