---
title: "DiagramShape"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una forma di disegno in un documento Visio."
type: docs
weight: 24
url: /it/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Rappresenta una forma di disegno in un documento Visio.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | Ottiene la pagina padre di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti. |
|
|  | [setWidth(double value)](#setWidth-double-) | Imposta la larghezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti. |
|
|  | [setHeight(double value)](#setHeight-double-) | Imposta l'altezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti. |
|
|  | [getX()](#getX--) | Ottiene lo spostamento orizzontale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo sinistro della pagina in punti. |
|
|  | [setX(double value)](#setX-double-) | Imposta lo spostamento orizzontale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo sinistro della pagina in punti. |
|
|  | [getY()](#getY--) | Ottiene lo spostamento verticale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo inferiore della pagina in punti. |
|
|  | [setY(double value)](#setY-double-) | Imposta lo spostamento verticale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo inferiore della pagina in punti. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene o imposta l'angolo di rotazione di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in gradi. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Ottiene o imposta l'angolo di rotazione di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in gradi. |
|
|  | [getText()](#getText--) | Ottiene o imposta il testo di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Ottiene la raccolta di frammenti di testo formattato di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getImage()](#getImage--) | Ottiene l'immagine di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Imposta l'immagine di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getId()](#getId--) | Ottiene l'identificatore di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getName()](#getName--) | Ottiene il nome di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getHyperlinks()](#getHyperlinks--) | Ottiene la raccolta di collegamenti ipertestuali associati a questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getAsposeShape()](#getAsposeShape--) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getPage() {#getPage--}
```
public final DiagramPage getPage()
```


Ottiene la pagina padre di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ottiene la larghezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti.


**Returns:**
double - La larghezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Imposta la larghezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La larghezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ottiene l'altezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti.


**Returns:**
double - L'altezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Imposta l'altezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'altezza di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punti. |
|

### getX() {#getX--}
```
public final double getX()
```


Ottiene lo spostamento orizzontale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo sinistro della pagina in punti.


**Returns:**
double - Lo spostamento orizzontale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo sinistro della pagina in punti.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Imposta lo spostamento orizzontale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo sinistro della pagina in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | Lo spostamento orizzontale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo sinistro della pagina in punti. |
|

### getY() {#getY--}
```
public final double getY()
```


Ottiene lo spostamento verticale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo inferiore della pagina in punti.


**Returns:**
double - Lo spostamento verticale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo inferiore della pagina in punti.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Imposta lo spostamento verticale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo inferiore della pagina in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | Lo spostamento verticale di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dal bordo inferiore della pagina in punti. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Ottiene o imposta l'angolo di rotazione di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in gradi.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Ottiene o imposta l'angolo di rotazione di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in gradi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'angolo di rotazione di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in gradi. |
|

### getText() {#getText--}
```
public final String getText()
```


Ottiene o imposta il testo di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - Il testo di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ottiene o imposta il testo di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Ottiene la raccolta di frammenti di testo formattato di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Ottiene l'immagine di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Imposta l'immagine di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | L'immagine di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Ottiene l'identificatore di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
long - L'identificatore di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - Il nome di questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Ottiene la raccolta di collegamenti ipertestuali associati a questo `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramHyperlinkCollection](../../com.groupdocs.watermark.contents/diagramhyperlinkcollection) - The collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getAsposeShape() {#getAsposeShape--}
```
public final Shape getAsposeShape()
```


<br />



**Returns:**
com.aspose.diagram.Shape
### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

