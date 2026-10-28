---
title: "DiagramHeaderFooterPossibleWatermark"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una possibile filigrana nell'intestazione/piè di pagina di un documento Visio."
type: docs
weight: 14
url: /it/java/com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class DiagramHeaderFooterPossibleWatermark extends PossibleWatermark
```

Rappresenta una possibile filigrana nell'intestazione/piè di pagina di un documento Visio.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DiagramHeaderFooterPossibleWatermark(DiagramContent content, int headerFooterType)](#DiagramHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.DiagramContent-int-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getParent()](#getParent--) | Ottiene il genitore di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in punti. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in punti. |
|
|  | [getX()](#getX--) | Ottiene lo spostamento orizzontale di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` dal bordo sinistro della pagina in punti. |
|
|  | [getY()](#getY--) | Ottiene lo spostamento verticale di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` dal bordo inferiore della pagina in punti. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene l'angolo di rotazione di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in gradi. |
|
|  | [getText()](#getText--) | Ottiene il testo di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il testo di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Ottiene il `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |
|
| [remove()](#remove--) |  |
### DiagramHeaderFooterPossibleWatermark(DiagramContent content, int headerFooterType) {#DiagramHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.DiagramContent-int-}
```
public DiagramHeaderFooterPossibleWatermark(DiagramContent content, int headerFooterType)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| content | [DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent) |  |
| headerFooterType | int |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Ottiene il genitore di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Ottiene la larghezza di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in punti.


**Returns:**
double - Il valore è sempre 0 per questo tipo di possibile watermark.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ottiene l'altezza di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in punti.


**Returns:**
double - Il valore è sempre 0 per questo tipo di possibile watermark.

### getX() {#getX--}
```
public double getX()
```


Ottiene lo spostamento orizzontale di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` dal bordo sinistro della pagina in punti.


**Returns:**
double - Il valore è sempre 0 per questo tipo di possibile watermark.

### getY() {#getY--}
```
public double getY()
```


Ottiene lo spostamento verticale di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` dal bordo inferiore della pagina in punti.


**Returns:**
double - Il valore è sempre 0 per questo tipo di possibile watermark.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Ottiene l'angolo di rotazione di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in gradi.


**Returns:**
double - Il valore è sempre 0 per questo tipo di possibile watermark.

### getText() {#getText--}
```
public String getText()
```


Ottiene il testo di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.


**Returns:**
java.lang.String - Il testo di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Imposta il testo di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |
|

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Ottiene il `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.


**Returns:**
int - Il `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.

### remove() {#remove--}
```
public void remove()
```




