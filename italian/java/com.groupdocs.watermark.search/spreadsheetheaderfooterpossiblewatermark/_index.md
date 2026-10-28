---
title: "SpreadsheetHeaderFooterPossibleWatermark"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un possibile watermark in un'intestazione o piè di pagina di un documento Excel."
type: docs
weight: 62
url: /it/java/com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class SpreadsheetHeaderFooterPossibleWatermark extends PossibleWatermark
```

Rappresenta un possibile watermark in un'intestazione o piè di pagina di un documento Excel.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section)](#SpreadsheetHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetHeaderFooterSection-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getParent()](#getParent--) | Ottiene il genitore di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` in punti. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` in punti. |
|
|  | [getX()](#getX--) | Ottiene l'offset orizzontale di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` dal bordo sinistro del foglio di lavoro in punti. |
|
|  | [getY()](#getY--) | Ottiene l'offset verticale di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` dal bordo superiore del foglio di lavoro in punti. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene l'angolo di rotazione di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` in gradi. |
|
|  | [getText()](#getText--) | Ottiene il testo di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il testo di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Ottiene l'`[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section) {#SpreadsheetHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetHeaderFooterSection-}
```
public SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Ottiene il genitore di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Ottiene la larghezza di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` in punti.


**Returns:**
double - La larghezza di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` in punti.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ottiene l'altezza di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` in punti.


**Returns:**
double - L'altezza di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` in punti.

### getX() {#getX--}
```
public double getX()
```


Ottiene l'offset orizzontale di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` dal bordo sinistro del foglio di lavoro in punti.


**Returns:**
double - La coordinata x di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Ottiene l'offset verticale di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` dal bordo superiore del foglio di lavoro in punti.


**Returns:**
double - La coordinata y di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Ottiene l'angolo di rotazione di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` in gradi.

### getText() {#getText--}
```
public String getText()
```


Ottiene il testo di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Returns:**
java.lang.String - Il testo di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Imposta il testo di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Ottiene l'`[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Returns:**
int - L'`[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

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




