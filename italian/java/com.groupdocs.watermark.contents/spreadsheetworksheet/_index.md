---
title: "SpreadsheetWorksheet"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un foglio di lavoro di un documento Excel."
type: docs
weight: 124
url: /it/java/com.groupdocs.watermark.contents/spreadsheetworksheet/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class SpreadsheetWorksheet extends ContentPart
```

Rappresenta un foglio di lavoro di un documento Excel.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSpreadsheetDataSizeInPoints()](#getSpreadsheetDataSizeInPoints--) |  |
|  | [getPageSetup()](#getPageSetup--) | Ottiene la configurazione di stampa della pagina per questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [getContentAreaWidth()](#getContentAreaWidth--) | Ottiene la larghezza dell'area di contenuto in punti. |
|
|  | [getContentAreaWidthPx()](#getContentAreaWidthPx--) | Ottiene la larghezza dell'area di contenuto in pixel. |
|
|  | [getContentAreaHeight()](#getContentAreaHeight--) | Ottiene l'altezza dell'area di contenuto in punti. |
|
|  | [getContentAreaHeightPx()](#getContentAreaHeightPx--) | Ottiene l'altezza dell'area di contenuto in pixel. |
|
|  | [getShapes()](#getShapes--) | Ottiene la raccolta di tutte le forme di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [getAttachments()](#getAttachments--) | Ottiene la raccolta di tutti gli allegati di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [getCharts()](#getCharts--) | Ottiene la raccolta di tutti i grafici di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Ottiene l'immagine di sfondo di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Imposta l'immagine di sfondo di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | Ottiene la raccolta di intestazioni e piè di pagina del foglio di lavoro. |
|
|  | [getAsposeCellsWorksheet()](#getAsposeCellsWorksheet--) | <br /> |

|
|  | [getColumnWidth(int column)](#getColumnWidth-int-) | Ottiene la larghezza della colonna specificata in punti. |
|
|  | [getColumnWidthPx(int column)](#getColumnWidthPx-int-) | Ottiene la larghezza della colonna specificata in pixel. |
|
|  | [getRowHeight(int row)](#getRowHeight-int-) | Ottiene l'altezza della riga specificata in punti. |
|
|  | [getRowHeightPx(int row)](#getRowHeightPx-int-) | Ottiene l'altezza della riga specificata in pixel. |
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


Ottiene la configurazione di stampa della pagina per questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Returns:**
[SpreadsheetPageSetup](../../com.groupdocs.watermark.contents/spreadsheetpagesetup) - The printing page setup for this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getContentAreaWidth() {#getContentAreaWidth--}
```
public final double getContentAreaWidth()
```


Ottiene la larghezza dell'area di contenuto in punti.


**Returns:**
double - La larghezza dell'area di contenuto in punti.

### getContentAreaWidthPx() {#getContentAreaWidthPx--}
```
public final int getContentAreaWidthPx()
```


Ottiene la larghezza dell'area di contenuto in pixel.


**Returns:**
int - La larghezza dell'area di contenuto in pixel.

### getContentAreaHeight() {#getContentAreaHeight--}
```
public final double getContentAreaHeight()
```


Ottiene l'altezza dell'area di contenuto in punti.


**Returns:**
double - L'altezza dell'area di contenuto in punti.

### getContentAreaHeightPx() {#getContentAreaHeightPx--}
```
public final int getContentAreaHeightPx()
```


Ottiene l'altezza dell'area di contenuto in pixel.


**Returns:**
int - L'altezza dell'area di contenuto in pixel.

### getShapes() {#getShapes--}
```
public final SpreadsheetShapeCollection getShapes()
```


Ottiene la raccolta di tutte le forme di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Returns:**
[SpreadsheetShapeCollection](../../com.groupdocs.watermark.contents/spreadsheetshapecollection) - The collection of all shapes of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getAttachments() {#getAttachments--}
```
public final SpreadsheetAttachmentCollection getAttachments()
```


Ottiene la raccolta di tutti gli allegati di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Returns:**
[SpreadsheetAttachmentCollection](../../com.groupdocs.watermark.contents/spreadsheetattachmentcollection) - The collection of all attachments of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getCharts() {#getCharts--}
```
public final SpreadsheetChartCollection getCharts()
```


Ottiene la raccolta di tutti i grafici di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Returns:**
[SpreadsheetChartCollection](../../com.groupdocs.watermark.contents/spreadsheetchartcollection) - The collection of all charts of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

### getBackgroundImage() {#getBackgroundImage--}
```
public final SpreadsheetWatermarkableImage getBackgroundImage()
```


Ottiene l'immagine di sfondo di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image of this `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` or `null` if the worksheet has no background image.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Imposta l'immagine di sfondo di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | L'immagine di sfondo di questo `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` o `null` se l'immagine di sfondo deve essere rimossa. |
|

### getHeadersFooters() {#getHeadersFooters--}
```
public final SpreadsheetHeaderFooterCollection getHeadersFooters()
```


Ottiene la raccolta di intestazioni e piè di pagina del foglio di lavoro.


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


Ottiene la larghezza della colonna specificata in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | colonna | int | L'indice della colonna. |
|

**Returns:**
double - La larghezza della colonna in punti.

### getColumnWidthPx(int column) {#getColumnWidthPx-int-}
```
public final int getColumnWidthPx(int column)
```


Ottiene la larghezza della colonna specificata in pixel.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | colonna | int | L'indice della colonna. |
|

**Returns:**
int - La larghezza della colonna in pixel.

### getRowHeight(int row) {#getRowHeight-int-}
```
public final double getRowHeight(int row)
```


Ottiene l'altezza della riga specificata in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | riga | int | L'indice della riga. |
|

**Returns:**
double - L'altezza della riga in punti.

### getRowHeightPx(int row) {#getRowHeightPx-int-}
```
public final int getRowHeightPx(int row)
```


Ottiene l'altezza della riga specificata in pixel.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | riga | int | L'indice della riga. |
|

**Returns:**
int - L'altezza della riga in pixel.

### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWordArtWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWordArtWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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



