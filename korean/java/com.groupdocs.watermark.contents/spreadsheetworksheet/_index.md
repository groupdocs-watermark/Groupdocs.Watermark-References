---
title: "SpreadsheetWorksheet"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서 워크시트를 나타냅니다."
type: docs
weight: 124
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetworksheet/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class SpreadsheetWorksheet extends ContentPart
```

Excel 문서 워크시트를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSpreadsheetDataSizeInPoints()](#getSpreadsheetDataSizeInPoints--) |  |
|  | [getPageSetup()](#getPageSetup--) | 이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`에 대한 인쇄 페이지 설정을 가져옵니다. |
|
|  | [getContentAreaWidth()](#getContentAreaWidth--) | 콘텐츠 영역의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getContentAreaWidthPx()](#getContentAreaWidthPx--) | 콘텐츠 영역의 너비를 픽셀 단위로 가져옵니다. |
|
|  | [getContentAreaHeight()](#getContentAreaHeight--) | 콘텐츠 영역의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getContentAreaHeightPx()](#getContentAreaHeightPx--) | 콘텐츠 영역의 높이를 픽셀 단위로 가져옵니다. |
|
|  | [getShapes()](#getShapes--) | 이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 모든 도형 컬렉션을 가져옵니다. |
|
|  | [getAttachments()](#getAttachments--) | 이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 모든 첨부 파일 컬렉션을 가져옵니다. |
|
|  | [getCharts()](#getCharts--) | 이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 모든 차트 컬렉션을 가져옵니다. |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | 이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 배경 이미지를 가져옵니다. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | 이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 배경 이미지를 설정합니다. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | 워크시트 머리글 및 바닥글 컬렉션을 가져옵니다. |
|
|  | [getAsposeCellsWorksheet()](#getAsposeCellsWorksheet--) | <br /> |

|
|  | [getColumnWidth(int column)](#getColumnWidth-int-) | 지정된 열의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getColumnWidthPx(int column)](#getColumnWidthPx-int-) | 지정된 열의 너비를 픽셀 단위로 가져옵니다. |
|
|  | [getRowHeight(int row)](#getRowHeight-int-) | 지정된 행의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getRowHeightPx(int row)](#getRowHeightPx-int-) | 지정된 행의 높이를 픽셀 단위로 가져옵니다. |
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


이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`에 대한 인쇄 페이지 설정을 가져옵니다.


**Returns:**
[SpreadsheetPageSetup](../../com.groupdocs.watermark.contents/spreadsheetpagesetup) - The printing page setup for this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getContentAreaWidth() {#getContentAreaWidth--}
```
public final double getContentAreaWidth()
```


콘텐츠 영역의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 콘텐츠 영역의 너비 (포인트).

### getContentAreaWidthPx() {#getContentAreaWidthPx--}
```
public final int getContentAreaWidthPx()
```


콘텐츠 영역의 너비를 픽셀 단위로 가져옵니다.


**Returns:**
int - 콘텐츠 영역의 너비 (픽셀).

### getContentAreaHeight() {#getContentAreaHeight--}
```
public final double getContentAreaHeight()
```


콘텐츠 영역의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 콘텐츠 영역의 높이 (포인트).

### getContentAreaHeightPx() {#getContentAreaHeightPx--}
```
public final int getContentAreaHeightPx()
```


콘텐츠 영역의 높이를 픽셀 단위로 가져옵니다.


**Returns:**
int - 콘텐츠 영역의 높이 (픽셀).

### getShapes() {#getShapes--}
```
public final SpreadsheetShapeCollection getShapes()
```


이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 모든 도형 컬렉션을 가져옵니다.


**Returns:**
[SpreadsheetShapeCollection](../../com.groupdocs.watermark.contents/spreadsheetshapecollection) - The collection of all shapes of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getAttachments() {#getAttachments--}
```
public final SpreadsheetAttachmentCollection getAttachments()
```


이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 모든 첨부 파일 컬렉션을 가져옵니다.


**Returns:**
[SpreadsheetAttachmentCollection](../../com.groupdocs.watermark.contents/spreadsheetattachmentcollection) - The collection of all attachments of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getCharts() {#getCharts--}
```
public final SpreadsheetChartCollection getCharts()
```


이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 모든 차트 컬렉션을 가져옵니다.


**Returns:**
[SpreadsheetChartCollection](../../com.groupdocs.watermark.contents/spreadsheetchartcollection) - The collection of all charts of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getBackgroundImage() {#getBackgroundImage--}
```
public final SpreadsheetWatermarkableImage getBackgroundImage()
```


이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 배경 이미지를 가져옵니다.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` or `null` if the worksheet has no background image.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 배경 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | 이 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`의 배경 이미지 또는 배경 이미지를 제거해야 하는 경우 `null`. |
|

### getHeadersFooters() {#getHeadersFooters--}
```
public final SpreadsheetHeaderFooterCollection getHeadersFooters()
```


워크시트 머리글 및 바닥글 컬렉션을 가져옵니다.


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


지정된 열의 너비를 포인트 단위로 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 열 | int | 열 인덱스. |
|

**Returns:**
double - 열의 너비(포인트 단위).

### getColumnWidthPx(int column) {#getColumnWidthPx-int-}
```
public final int getColumnWidthPx(int column)
```


지정된 열의 너비를 픽셀 단위로 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 열 | int | 열 인덱스. |
|

**Returns:**
int - 열의 너비(픽셀 단위).

### getRowHeight(int row) {#getRowHeight-int-}
```
public final double getRowHeight(int row)
```


지정된 행의 높이를 포인트 단위로 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | row | int | 행 인덱스. |
|

**Returns:**
double - 행의 높이(포인트 단위).

### getRowHeightPx(int row) {#getRowHeightPx-int-}
```
public final int getRowHeightPx(int row)
```


지정된 행의 높이를 픽셀 단위로 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | row | int | 행 인덱스. |
|

**Returns:**
int - 행의 높이(픽셀 단위).

### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
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



