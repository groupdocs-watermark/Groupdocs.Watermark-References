---
title: "SpreadsheetWorksheet"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Excel belgesi bir çalışma sayfasını temsil eder."
type: docs
weight: 124
url: /tr/java/com.groupdocs.watermark.contents/spreadsheetworksheet/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class SpreadsheetWorksheet extends ContentPart
```

Excel belgesi bir çalışma sayfasını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSpreadsheetDataSizeInPoints()](#getSpreadsheetDataSizeInPoints--) |  |
|  | [getPageSetup()](#getPageSetup--) | Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` için yazdırma sayfa ayarını alır. |
|
|  | [getContentAreaWidth()](#getContentAreaWidth--) | İçerik alanının genişliğini nokta cinsinden alır. |
|
|  | [getContentAreaWidthPx()](#getContentAreaWidthPx--) | İçerik alanının genişliğini piksel cinsinden alır. |
|
|  | [getContentAreaHeight()](#getContentAreaHeight--) | İçerik alanının yüksekliğini nokta cinsinden alır. |
|
|  | [getContentAreaHeightPx()](#getContentAreaHeightPx--) | İçerik alanının yüksekliğini piksel cinsinden alır. |
|
|  | [getShapes()](#getShapes--) | Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` içindeki tüm şekillerin koleksiyonunu alır. |
|
|  | [getAttachments()](#getAttachments--) | Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` içindeki tüm eklerin koleksiyonunu alır. |
|
|  | [getCharts()](#getCharts--) | Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` içindeki tüm grafiklerin koleksiyonunu alır. |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` arka plan resmini alır. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` arka plan resmini ayarlar. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | Çalışma sayfası başlık ve altbilgilerinin koleksiyonunu alır. |
|
|  | [getAsposeCellsWorksheet()](#getAsposeCellsWorksheet--) | <br /> |

|
|  | [getColumnWidth(int column)](#getColumnWidth-int-) | Belirtilen sütunun genişliğini nokta cinsinden alır. |
|
|  | [getColumnWidthPx(int column)](#getColumnWidthPx-int-) | Belirtilen sütunun genişliğini piksel cinsinden alır. |
|
|  | [getRowHeight(int row)](#getRowHeight-int-) | Belirtilen satırın yüksekliğini nokta cinsinden alır. |
|
|  | [getRowHeightPx(int row)](#getRowHeightPx-int-) | Belirtilen satırın yüksekliğini piksel cinsinden alır. |
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


Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` için yazdırma sayfa ayarını alır.


**Returns:**
[SpreadsheetPageSetup](../../com.groupdocs.watermark.contents/spreadsheetpagesetup) - The printing page setup for this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getContentAreaWidth() {#getContentAreaWidth--}
```
public final double getContentAreaWidth()
```


İçerik alanının genişliğini nokta cinsinden alır.


**Returns:**
double - İçerik alanının genişliği nokta cinsinden.

### getContentAreaWidthPx() {#getContentAreaWidthPx--}
```
public final int getContentAreaWidthPx()
```


İçerik alanının genişliğini piksel cinsinden alır.


**Returns:**
int - İçerik alanının genişliği piksel cinsinden.

### getContentAreaHeight() {#getContentAreaHeight--}
```
public final double getContentAreaHeight()
```


İçerik alanının yüksekliğini nokta cinsinden alır.


**Returns:**
double - İçerik alanının yüksekliği nokta cinsinden.

### getContentAreaHeightPx() {#getContentAreaHeightPx--}
```
public final int getContentAreaHeightPx()
```


İçerik alanının yüksekliğini piksel cinsinden alır.


**Returns:**
int - İçerik alanının yüksekliği piksel cinsinden.

### getShapes() {#getShapes--}
```
public final SpreadsheetShapeCollection getShapes()
```


Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` içindeki tüm şekillerin koleksiyonunu alır.


**Returns:**
[SpreadsheetShapeCollection](../../com.groupdocs.watermark.contents/spreadsheetshapecollection) - The collection of all shapes of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getAttachments() {#getAttachments--}
```
public final SpreadsheetAttachmentCollection getAttachments()
```


Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` içindeki tüm eklerin koleksiyonunu alır.


**Returns:**
[SpreadsheetAttachmentCollection](../../com.groupdocs.watermark.contents/spreadsheetattachmentcollection) - The collection of all attachments of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getCharts() {#getCharts--}
```
public final SpreadsheetChartCollection getCharts()
```


Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` içindeki tüm grafiklerin koleksiyonunu alır.


**Returns:**
[SpreadsheetChartCollection](../../com.groupdocs.watermark.contents/spreadsheetchartcollection) - The collection of all charts of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getBackgroundImage() {#getBackgroundImage--}
```
public final SpreadsheetWatermarkableImage getBackgroundImage()
```


Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` arka plan resmini alır.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` or `null` if the worksheet has no background image.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` arka plan resmini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Bu `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` arka plan resmi veya arka plan resmi kaldırılacaksa `null`. |
|

### getHeadersFooters() {#getHeadersFooters--}
```
public final SpreadsheetHeaderFooterCollection getHeadersFooters()
```


Çalışma sayfası başlık ve altbilgilerinin koleksiyonunu alır.


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


Belirtilen sütunun genişliğini nokta cinsinden alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | sütun | int | Sütun indeksi. |
|

**Returns:**
double - Sütunun genişliği puan cinsinden.

### getColumnWidthPx(int column) {#getColumnWidthPx-int-}
```
public final int getColumnWidthPx(int column)
```


Belirtilen sütunun genişliğini piksel cinsinden alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | sütun | int | Sütun indeksi. |
|

**Returns:**
int - Sütunun genişliği piksel cinsinden.

### getRowHeight(int row) {#getRowHeight-int-}
```
public final double getRowHeight(int row)
```


Belirtilen satırın yüksekliğini nokta cinsinden alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | satır | int | Satır indeksi. |
|

**Returns:**
double - Satırın yüksekliği puan cinsinden.

### getRowHeightPx(int row) {#getRowHeightPx-int-}
```
public final int getRowHeightPx(int row)
```


Belirtilen satırın yüksekliğini piksel cinsinden alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | satır | int | Satır indeksi. |
|

**Returns:**
int - Satırın yüksekliği piksel cinsinden.

### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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



