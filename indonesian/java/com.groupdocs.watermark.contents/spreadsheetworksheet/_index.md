---
title: "SpreadsheetWorksheet"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili lembar kerja dokumen Excel."
type: docs
weight: 124
url: /id/java/com.groupdocs.watermark.contents/spreadsheetworksheet/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class SpreadsheetWorksheet extends ContentPart
```

Mewakili lembar kerja dokumen Excel.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSpreadsheetDataSizeInPoints()](#getSpreadsheetDataSizeInPoints--) |  |
|  | [getPageSetup()](#getPageSetup--) | Mendapatkan pengaturan halaman cetak untuk `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini. |
|
|  | [getContentAreaWidth()](#getContentAreaWidth--) | Mendapatkan lebar area konten dalam poin. |
|
|  | [getContentAreaWidthPx()](#getContentAreaWidthPx--) | Mendapatkan lebar area konten dalam piksel. |
|
|  | [getContentAreaHeight()](#getContentAreaHeight--) | Mendapatkan tinggi area konten dalam poin. |
|
|  | [getContentAreaHeightPx()](#getContentAreaHeightPx--) | Mendapatkan tinggi area konten dalam piksel. |
|
|  | [getShapes()](#getShapes--) | Mendapatkan koleksi semua bentuk dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini. |
|
|  | [getAttachments()](#getAttachments--) | Mendapatkan koleksi semua lampiran dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini. |
|
|  | [getCharts()](#getCharts--) | Mendapatkan koleksi semua diagram dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini. |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Mendapatkan gambar latar dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Mengatur gambar latar dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | Mendapatkan koleksi header dan footer lembar kerja. |
|
|  | [getAsposeCellsWorksheet()](#getAsposeCellsWorksheet--) | <br /> |

|
|  | [getColumnWidth(int column)](#getColumnWidth-int-) | Mendapatkan lebar kolom yang ditentukan dalam poin. |
|
|  | [getColumnWidthPx(int column)](#getColumnWidthPx-int-) | Mendapatkan lebar kolom yang ditentukan dalam piksel. |
|
|  | [getRowHeight(int row)](#getRowHeight-int-) | Mendapatkan tinggi baris yang ditentukan dalam poin. |
|
|  | [getRowHeightPx(int row)](#getRowHeightPx-int-) | Mendapatkan tinggi baris yang ditentukan dalam piksel. |
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


Mendapatkan pengaturan halaman cetak untuk `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini.


**Returns:**
[SpreadsheetPageSetup](../../com.groupdocs.watermark.contents/spreadsheetpagesetup) - The printing page setup for this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getContentAreaWidth() {#getContentAreaWidth--}
```
public final double getContentAreaWidth()
```


Mendapatkan lebar area konten dalam poin.


**Returns:**
double - Lebar area konten dalam poin.

### getContentAreaWidthPx() {#getContentAreaWidthPx--}
```
public final int getContentAreaWidthPx()
```


Mendapatkan lebar area konten dalam piksel.


**Returns:**
int - Lebar area konten dalam piksel.

### getContentAreaHeight() {#getContentAreaHeight--}
```
public final double getContentAreaHeight()
```


Mendapatkan tinggi area konten dalam poin.


**Returns:**
double - Tinggi area konten dalam poin.

### getContentAreaHeightPx() {#getContentAreaHeightPx--}
```
public final int getContentAreaHeightPx()
```


Mendapatkan tinggi area konten dalam piksel.


**Returns:**
int - Tinggi area konten dalam piksel.

### getShapes() {#getShapes--}
```
public final SpreadsheetShapeCollection getShapes()
```


Mendapatkan koleksi semua bentuk dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini.


**Returns:**
[SpreadsheetShapeCollection](../../com.groupdocs.watermark.contents/spreadsheetshapecollection) - The collection of all shapes of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getAttachments() {#getAttachments--}
```
public final SpreadsheetAttachmentCollection getAttachments()
```


Mendapatkan koleksi semua lampiran dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini.


**Returns:**
[SpreadsheetAttachmentCollection](../../com.groupdocs.watermark.contents/spreadsheetattachmentcollection) - The collection of all attachments of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getCharts() {#getCharts--}
```
public final SpreadsheetChartCollection getCharts()
```


Mendapatkan koleksi semua diagram dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini.


**Returns:**
[SpreadsheetChartCollection](../../com.groupdocs.watermark.contents/spreadsheetchartcollection) - The collection of all charts of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getBackgroundImage() {#getBackgroundImage--}
```
public final SpreadsheetWatermarkableImage getBackgroundImage()
```


Mendapatkan gambar latar dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` or `null` if the worksheet has no background image.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Mengatur gambar latar dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Gambar latar dari `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ini atau `null` jika gambar latar harus dihapus. |
|

### getHeadersFooters() {#getHeadersFooters--}
```
public final SpreadsheetHeaderFooterCollection getHeadersFooters()
```


Mendapatkan koleksi header dan footer lembar kerja.


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


Mendapatkan lebar kolom yang ditentukan dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kolom | int | Indeks kolom. |
|

**Returns:**
double - Lebar kolom dalam poin.

### getColumnWidthPx(int column) {#getColumnWidthPx-int-}
```
public final int getColumnWidthPx(int column)
```


Mendapatkan lebar kolom yang ditentukan dalam piksel.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kolom | int | Indeks kolom. |
|

**Returns:**
int - Lebar kolom dalam piksel.

### getRowHeight(int row) {#getRowHeight-int-}
```
public final double getRowHeight(int row)
```


Mendapatkan tinggi baris yang ditentukan dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | baris | int | Indeks baris. |
|

**Returns:**
double - Tinggi baris dalam poin.

### getRowHeightPx(int row) {#getRowHeightPx-int-}
```
public final int getRowHeightPx(int row)
```


Mendapatkan tinggi baris yang ditentukan dalam piksel.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | baris | int | Indeks baris. |
|

**Returns:**
int - Tinggi baris dalam piksel.

### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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



