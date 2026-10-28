---
title: "SpreadsheetWorksheet"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een werkblad van een Excel‑document voor."
type: docs
weight: 124
url: /nl/java/com.groupdocs.watermark.contents/spreadsheetworksheet/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class SpreadsheetWorksheet extends ContentPart
```

Stelt een werkblad van een Excel‑document voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSpreadsheetDataSizeInPoints()](#getSpreadsheetDataSizeInPoints--) |  |
|  | [getPageSetup()](#getPageSetup--) | Haalt de afdrukpagina‑instelling op voor deze `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [getContentAreaWidth()](#getContentAreaWidth--) | Haalt de breedte van het inhoudsgebied op in punten. |
|
|  | [getContentAreaWidthPx()](#getContentAreaWidthPx--) | Haalt de breedte van het inhoudsgebied op in pixels. |
|
|  | [getContentAreaHeight()](#getContentAreaHeight--) | Haalt de hoogte van het inhoudsgebied op in punten. |
|
|  | [getContentAreaHeightPx()](#getContentAreaHeightPx--) | Haalt de hoogte van het inhoudsgebied op in pixels. |
|
|  | [getShapes()](#getShapes--) | Haalt de verzameling van alle vormen van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` op. |
|
|  | [getAttachments()](#getAttachments--) | Haalt de verzameling van alle bijlagen van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` op. |
|
|  | [getCharts()](#getCharts--) | Haalt de verzameling van alle grafieken van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` op. |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Haalt de achtergrondafbeelding van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` op. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Stelt de achtergrondafbeelding van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` in. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | Haalt de verzameling van werkbladkoppen en -voetteksten op. |
|
|  | [getAsposeCellsWorksheet()](#getAsposeCellsWorksheet--) | <br /> |

|
|  | [getColumnWidth(int column)](#getColumnWidth-int-) | Haalt de breedte van de opgegeven kolom op in punten. |
|
|  | [getColumnWidthPx(int column)](#getColumnWidthPx-int-) | Haalt de breedte van de opgegeven kolom op in pixels. |
|
|  | [getRowHeight(int row)](#getRowHeight-int-) | Haalt de hoogte van de opgegeven rij op in punten. |
|
|  | [getRowHeightPx(int row)](#getRowHeightPx-int-) | Haalt de hoogte van de opgegeven rij op in pixels. |
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


Haalt de afdrukpagina‑instelling op voor deze `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Returns:**
[SpreadsheetPageSetup](../../com.groupdocs.watermark.contents/spreadsheetpagesetup) - The printing page setup for this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getContentAreaWidth() {#getContentAreaWidth--}
```
public final double getContentAreaWidth()
```


Haalt de breedte van het inhoudsgebied op in punten.


**Returns:**
double - De breedte van het inhoudsgebied in punten.

### getContentAreaWidthPx() {#getContentAreaWidthPx--}
```
public final int getContentAreaWidthPx()
```


Haalt de breedte van het inhoudsgebied op in pixels.


**Returns:**
int - De breedte van het inhoudsgebied in pixels.

### getContentAreaHeight() {#getContentAreaHeight--}
```
public final double getContentAreaHeight()
```


Haalt de hoogte van het inhoudsgebied op in punten.


**Returns:**
double - De hoogte van het inhoudsgebied in punten.

### getContentAreaHeightPx() {#getContentAreaHeightPx--}
```
public final int getContentAreaHeightPx()
```


Haalt de hoogte van het inhoudsgebied op in pixels.


**Returns:**
int - De hoogte van het inhoudsgebied in pixels.

### getShapes() {#getShapes--}
```
public final SpreadsheetShapeCollection getShapes()
```


Haalt de verzameling van alle vormen van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` op.


**Returns:**
[SpreadsheetShapeCollection](../../com.groupdocs.watermark.contents/spreadsheetshapecollection) - The collection of all shapes of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getAttachments() {#getAttachments--}
```
public final SpreadsheetAttachmentCollection getAttachments()
```


Haalt de verzameling van alle bijlagen van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` op.


**Returns:**
[SpreadsheetAttachmentCollection](../../com.groupdocs.watermark.contents/spreadsheetattachmentcollection) - The collection of all attachments of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getCharts() {#getCharts--}
```
public final SpreadsheetChartCollection getCharts()
```


Haalt de verzameling van alle grafieken van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` op.


**Returns:**
[SpreadsheetChartCollection](../../com.groupdocs.watermark.contents/spreadsheetchartcollection) - The collection of all charts of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getBackgroundImage() {#getBackgroundImage--}
```
public final SpreadsheetWatermarkableImage getBackgroundImage()
```


Haalt de achtergrondafbeelding van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` op.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` or `null` if the worksheet has no background image.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Stelt de achtergrondafbeelding van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | De achtergrondafbeelding van dit `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` of `null` als de achtergrondafbeelding moet worden verwijderd. |
|

### getHeadersFooters() {#getHeadersFooters--}
```
public final SpreadsheetHeaderFooterCollection getHeadersFooters()
```


Haalt de verzameling van werkbladkoppen en -voetteksten op.


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


Haalt de breedte van de opgegeven kolom op in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | kolom | int | De kolomindex. |
|

**Returns:**
double - De breedte van de kolom in punten.

### getColumnWidthPx(int column) {#getColumnWidthPx-int-}
```
public final int getColumnWidthPx(int column)
```


Haalt de breedte van de opgegeven kolom op in pixels.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | kolom | int | De kolomindex. |
|

**Returns:**
int - De breedte van de kolom in pixels.

### getRowHeight(int row) {#getRowHeight-int-}
```
public final double getRowHeight(int row)
```


Haalt de hoogte van de opgegeven rij op in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | rij | int | De rij-index. |
|

**Returns:**
double - De hoogte van de rij in punten.

### getRowHeightPx(int row) {#getRowHeightPx-int-}
```
public final int getRowHeightPx(int row)
```


Haalt de hoogte van de opgegeven rij op in pixels.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | rij | int | De rij-index. |
|

**Returns:**
int - De hoogte van de rij in pixels.

### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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



