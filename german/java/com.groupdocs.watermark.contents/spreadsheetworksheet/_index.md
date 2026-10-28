---
title: "SpreadsheetWorksheet"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Excel-Dokument-Arbeitsblatt dar."
type: docs
weight: 124
url: /de/java/com.groupdocs.watermark.contents/spreadsheetworksheet/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class SpreadsheetWorksheet extends ContentPart
```

Stellt ein Excel-Dokument-Arbeitsblatt dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSpreadsheetDataSizeInPoints()](#getSpreadsheetDataSizeInPoints--) |  |
|  | [getPageSetup()](#getPageSetup--) | Ruft die Druckseiteneinrichtung für dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab. |
|
|  | [getContentAreaWidth()](#getContentAreaWidth--) | Ruft die Breite des Inhaltsbereichs in Punkten ab. |
|
|  | [getContentAreaWidthPx()](#getContentAreaWidthPx--) | Ruft die Breite des Inhaltsbereichs in Pixeln ab. |
|
|  | [getContentAreaHeight()](#getContentAreaHeight--) | Ruft die Höhe des Inhaltsbereichs in Punkten ab. |
|
|  | [getContentAreaHeightPx()](#getContentAreaHeightPx--) | Ruft die Höhe des Inhaltsbereichs in Pixeln ab. |
|
|  | [getShapes()](#getShapes--) | Ruft die Sammlung aller Formen dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab. |
|
|  | [getAttachments()](#getAttachments--) | Ruft die Sammlung aller Anhänge dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab. |
|
|  | [getCharts()](#getCharts--) | Ruft die Sammlung aller Diagramme dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab. |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Ruft das Hintergrundbild dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Setzt das Hintergrundbild dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | Ruft die Sammlung der Arbeitsblatt‑Kopf‑ und Fußzeilen ab. |
|
|  | [getAsposeCellsWorksheet()](#getAsposeCellsWorksheet--) | <br /> |

|
|  | [getColumnWidth(int column)](#getColumnWidth-int-) | Ruft die Breite der angegebenen Spalte in Punkten ab. |
|
|  | [getColumnWidthPx(int column)](#getColumnWidthPx-int-) | Ruft die Breite der angegebenen Spalte in Pixeln ab. |
|
|  | [getRowHeight(int row)](#getRowHeight-int-) | Ruft die Höhe der angegebenen Zeile in Punkten ab. |
|
|  | [getRowHeightPx(int row)](#getRowHeightPx-int-) | Ruft die Höhe der angegebenen Zeile in Pixeln ab. |
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


Ruft die Druckseiteneinrichtung für dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab.


**Returns:**
[SpreadsheetPageSetup](../../com.groupdocs.watermark.contents/spreadsheetpagesetup) - The printing page setup for this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getContentAreaWidth() {#getContentAreaWidth--}
```
public final double getContentAreaWidth()
```


Ruft die Breite des Inhaltsbereichs in Punkten ab.


**Returns:**
double - Die Breite des Inhaltsbereichs in Punkten.

### getContentAreaWidthPx() {#getContentAreaWidthPx--}
```
public final int getContentAreaWidthPx()
```


Ruft die Breite des Inhaltsbereichs in Pixeln ab.


**Returns:**
int - Die Breite des Inhaltsbereichs in Pixeln.

### getContentAreaHeight() {#getContentAreaHeight--}
```
public final double getContentAreaHeight()
```


Ruft die Höhe des Inhaltsbereichs in Punkten ab.


**Returns:**
double - Die Höhe des Inhaltsbereichs in Punkten.

### getContentAreaHeightPx() {#getContentAreaHeightPx--}
```
public final int getContentAreaHeightPx()
```


Ruft die Höhe des Inhaltsbereichs in Pixeln ab.


**Returns:**
int - Die Höhe des Inhaltsbereichs in Pixeln.

### getShapes() {#getShapes--}
```
public final SpreadsheetShapeCollection getShapes()
```


Ruft die Sammlung aller Formen dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab.


**Returns:**
[SpreadsheetShapeCollection](../../com.groupdocs.watermark.contents/spreadsheetshapecollection) - The collection of all shapes of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getAttachments() {#getAttachments--}
```
public final SpreadsheetAttachmentCollection getAttachments()
```


Ruft die Sammlung aller Anhänge dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab.


**Returns:**
[SpreadsheetAttachmentCollection](../../com.groupdocs.watermark.contents/spreadsheetattachmentcollection) - The collection of all attachments of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getCharts() {#getCharts--}
```
public final SpreadsheetChartCollection getCharts()
```


Ruft die Sammlung aller Diagramme dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab.


**Returns:**
[SpreadsheetChartCollection](../../com.groupdocs.watermark.contents/spreadsheetchartcollection) - The collection of all charts of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getBackgroundImage() {#getBackgroundImage--}
```
public final SpreadsheetWatermarkableImage getBackgroundImage()
```


Ruft das Hintergrundbild dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` ab.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` or `null` if the worksheet has no background image.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Setzt das Hintergrundbild dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Das Hintergrundbild dieses `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` oder `null`, wenn das Hintergrundbild entfernt werden soll. |
|

### getHeadersFooters() {#getHeadersFooters--}
```
public final SpreadsheetHeaderFooterCollection getHeadersFooters()
```


Ruft die Sammlung der Arbeitsblatt‑Kopf‑ und Fußzeilen ab.


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


Ruft die Breite der angegebenen Spalte in Punkten ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Spalte | int | Der Spaltenindex. |
|

**Returns:**
double - Die Breite der Spalte in Punkten.

### getColumnWidthPx(int column) {#getColumnWidthPx-int-}
```
public final int getColumnWidthPx(int column)
```


Ruft die Breite der angegebenen Spalte in Pixeln ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Spalte | int | Der Spaltenindex. |
|

**Returns:**
int - Die Breite der Spalte in Pixeln.

### getRowHeight(int row) {#getRowHeight-int-}
```
public final double getRowHeight(int row)
```


Ruft die Höhe der angegebenen Zeile in Punkten ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Zeile | int | Der Zeilenindex. |
|

**Returns:**
double - Die Höhe der Zeile in Punkten.

### getRowHeightPx(int row) {#getRowHeightPx-int-}
```
public final int getRowHeightPx(int row)
```


Ruft die Höhe der angegebenen Zeile in Pixeln ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Zeile | int | Der Zeilenindex. |
|

**Returns:**
int - Die Höhe der Zeile in Pixeln.

### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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



