---
title: "SpreadsheetShape"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una forma di disegno in un documento Excel."
type: docs
weight: 117
url: /it/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Rappresenta una forma di disegno in un documento Excel.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Restituisce il foglio di lavoro genitore di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | Restituisce il tipo di forma automatica. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | Restituisce il tipo di disegno mso. |
|
|  | [getText()](#getText--) | Restituisce il testo di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il testo di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Restituisce la collezione di frammenti di testo formattato di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImage()](#getImage--) | Restituisce l'immagine di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Imposta l'immagine di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Restituisce le impostazioni del formato di riempimento immagine di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getId()](#getId--) | Restituisce l'identificatore di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Restituisce il testo descrittivo (alternativo) associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Imposta il testo descrittivo (alternativo) associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [isWordArt()](#isWordArt--) | Restituisce un valore che indica se questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` è un oggetto WordArt. |
|
|  | [getName()](#getName--) | Restituisce il nome di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | Restituisce il collegamento ipertestuale associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Imposta il collegamento ipertestuale associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getX()](#getX--) | Restituisce lo spostamento orizzontale di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` dal bordo sinistro del foglio di lavoro in punti. |
|
|  | [setX(double value)](#setX-double-) | Imposta lo spostamento orizzontale di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` dal bordo sinistro del foglio di lavoro in punti. |
|
|  | [getY()](#getY--) | Restituisce lo spostamento verticale di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` dal bordo superiore del foglio di lavoro in punti. |
|
|  | [setY(double value)](#setY-double-) | Imposta lo spostamento verticale di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` dal bordo superiore del foglio di lavoro in punti. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti. |
|
|  | [setWidth(double value)](#setWidth-double-) | Imposta la larghezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti. |
|
|  | [setHeight(double value)](#setHeight-double-) | Imposta l'altezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene o imposta l'angolo di rotazione di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in gradi. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Ottiene o imposta l'angolo di rotazione di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in gradi. |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Restituisce il foglio di lavoro genitore di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Restituisce il tipo di forma automatica.


**Returns:**
int - Il tipo di forma automatica.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


Restituisce il tipo di disegno mso.


**Returns:**
int - Il tipo di disegno mso.

### getText() {#getText--}
```
public final String getText()
```


Restituisce il testo di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Il testo di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Imposta il testo di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Restituisce la collezione di frammenti di testo formattato di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Restituisce l'immagine di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Imposta l'immagine di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | L'immagine di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` o null se l'immagine deve essere rimossa. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Restituisce le impostazioni del formato di riempimento immagine di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


Restituisce l'identificatore di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
int - L'identificatore di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Restituisce il testo descrittivo (alternativo) associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Il testo descrittivo (alternativo) associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Imposta il testo descrittivo (alternativo) associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo descrittivo (alternativo) associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Restituisce un valore che indica se questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` è un oggetto WordArt.


**Returns:**
boolean - True se la forma è un oggetto WordArt; altrimenti, false.

### getName() {#getName--}
```
public final String getName()
```


Restituisce il nome di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Il nome di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Restituisce il collegamento ipertestuale associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Il collegamento ipertestuale associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Imposta il collegamento ipertestuale associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il collegamento ipertestuale associato a questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Restituisce lo spostamento orizzontale di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` dal bordo sinistro del foglio di lavoro in punti.


**Returns:**
double - La coordinata x di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Imposta lo spostamento orizzontale di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` dal bordo sinistro del foglio di lavoro in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La coordinata x di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Restituisce lo spostamento verticale di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` dal bordo superiore del foglio di lavoro in punti.


**Returns:**
double - La coordinata y di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Imposta lo spostamento verticale di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` dal bordo superiore del foglio di lavoro in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La coordinata y di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ottiene la larghezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti.


**Returns:**
double - La larghezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Imposta la larghezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La larghezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ottiene l'altezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti.


**Returns:**
double - L'altezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Imposta l'altezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'altezza di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punti. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Ottiene o imposta l'angolo di rotazione di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in gradi.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Ottiene o imposta l'angolo di rotazione di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in gradi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'angolo di rotazione di questo `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in gradi. |
|

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageData | byte[] |  |

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

