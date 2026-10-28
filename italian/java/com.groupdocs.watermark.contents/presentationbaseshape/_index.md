---
title: "PresentationBaseShape"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce la classe base astratta per le forme di tutti i tipi in un documento PowerPoint."
type: docs
weight: 77
url: /it/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

Fornisce la classe base astratta per le forme di tutti i tipi in un documento PowerPoint.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | Ottiene la presentazione principale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Ottiene le impostazioni del formato di riempimento immagine di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getName()](#getName--) | Ottiene il nome di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Ottiene il testo descrittivo (alternativo) associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Imposta il testo descrittivo (alternativo) associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getId()](#getId--) | Ottiene l'identificatore di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | Ottiene la posizione di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` nell'ordine Z. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Ottiene il collegamento ipertestuale associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Imposta il collegamento ipertestuale associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getX()](#getX--) | Ottiene lo spostamento orizzontale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dal bordo sinistro della presentazione in punti. |
|
|  | [setX(double value)](#setX-double-) | Imposta lo spostamento orizzontale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dal bordo sinistro della presentazione in punti. |
|
|  | [getY()](#getY--) | Ottiene o imposta lo spostamento verticale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dal bordo superiore della presentazione in punti. |
|
|  | [setY(double value)](#setY-double-) | Ottiene o imposta lo spostamento verticale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dal bordo superiore della presentazione in punti. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti. |
|
|  | [setWidth(double value)](#setWidth-double-) | Imposta la larghezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti. |
|
|  | [setHeight(double value)](#setHeight-double-) | Imposta l'altezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Ottiene la presentazione principale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Ottiene le impostazioni del formato di riempimento immagine di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - Il nome di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Ottiene il testo descrittivo (alternativo) associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - Il testo descrittivo (alternativo) associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Imposta il testo descrittivo (alternativo) associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo descrittivo (alternativo) associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Ottiene l'identificatore di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
long - L'identificatore di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Ottiene la posizione di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` nell'ordine Z.

Una forma con ordine Z più alto è sempre davanti a una forma con ordine Z più basso.


**Returns:**
int - La posizione di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` nell'ordine Z.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Ottiene il collegamento ipertestuale associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | actionType | int | L'azione che attiva il collegamento ipertestuale. |
|

**Returns:**
java.lang.String - L'URL del collegamento ipertestuale che viene attivato sull'azione specificata.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Imposta il collegamento ipertestuale associato a questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | actionType | int | L'azione che attiva il collegamento ipertestuale. |
|
|  | URL | java.lang.String | L'URL del collegamento ipertestuale. |
|

### getX() {#getX--}
```
public final double getX()
```


Ottiene lo spostamento orizzontale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dal bordo sinistro della presentazione in punti.


**Returns:**
double - La coordinata X di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Imposta lo spostamento orizzontale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dal bordo sinistro della presentazione in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La coordinata X di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Ottiene o imposta lo spostamento verticale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dal bordo superiore della presentazione in punti.


**Returns:**
double - La coordinata Y di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ottiene o imposta lo spostamento verticale di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dal bordo superiore della presentazione in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La coordinata y di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ottiene la larghezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti.


**Returns:**
double - La larghezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Imposta la larghezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La larghezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ottiene l'altezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti.


**Returns:**
double - L'altezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Imposta l'altezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'altezza di questo `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punti. |
|

