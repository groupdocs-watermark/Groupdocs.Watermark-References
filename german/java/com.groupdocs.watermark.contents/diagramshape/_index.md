---
title: "DiagramShape"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Zeichnungsform in einem Visio-Dokument dar."
type: docs
weight: 24
url: /de/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Stellt eine Zeichnungsform in einem Visio-Dokument dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | Gibt die übergeordnete Seite dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück. |
|
|  | [getWidth()](#getWidth--) | Gibt die Breite dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten zurück. |
|
|  | [setWidth(double value)](#setWidth-double-) | Setzt die Breite dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten. |
|
|  | [getHeight()](#getHeight--) | Gibt die Höhe dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten zurück. |
|
|  | [setHeight(double value)](#setHeight-double-) | Setzt die Höhe dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten. |
|
|  | [getX()](#getX--) | Gibt den horizontalen Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom linken Seitenrand in Punkten zurück. |
|
|  | [setX(double value)](#setX-double-) | Setzt den horizontalen Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom linken Seitenrand in Punkten. |
|
|  | [getY()](#getY--) | Gibt den vertikalen Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom unteren Seitenrand in Punkten zurück. |
|
|  | [setY(double value)](#setY-double-) | Setzt den vertikalen Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom unteren Seitenrand in Punkten. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Liest oder setzt den Rotationswinkel dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Grad. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Liest oder setzt den Rotationswinkel dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Grad. |
|
|  | [getText()](#getText--) | Liest oder setzt den Text dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Text dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Gibt die Sammlung formatierter Textfragmente dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück. |
|
|  | [getImage()](#getImage--) | Gibt das Bild dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Setzt das Bild dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getId()](#getId--) | Gibt den Bezeichner dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück. |
|
|  | [getName()](#getName--) | Gibt den Namen dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück. |
|
|  | [getHyperlinks()](#getHyperlinks--) | Gibt die Sammlung von Hyperlinks zurück, die an diesem `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` angehängt sind. |
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


Gibt die übergeordnete Seite dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gibt die Breite dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten zurück.


**Returns:**
double - Die Breite dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Setzt die Breite dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die Breite dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gibt die Höhe dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten zurück.


**Returns:**
double - Die Höhe dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Setzt die Höhe dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die Höhe dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Punkten. |
|

### getX() {#getX--}
```
public final double getX()
```


Gibt den horizontalen Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom linken Seitenrand in Punkten zurück.


**Returns:**
double - Der horizontale Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom linken Seitenrand der Seite in Punkten.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Setzt den horizontalen Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom linken Seitenrand in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Der horizontale Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom linken Seitenrand der Seite in Punkten. |
|

### getY() {#getY--}
```
public final double getY()
```


Gibt den vertikalen Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom unteren Seitenrand in Punkten zurück.


**Returns:**
double - Der vertikale Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom unteren Seitenrand der Seite in Punkten.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Setzt den vertikalen Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom unteren Seitenrand in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Der vertikale Versatz dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vom unteren Seitenrand der Seite in Punkten. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Liest oder setzt den Rotationswinkel dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Grad.


**Returns:**
double - Der Rotationswinkel dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Grad.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Liest oder setzt den Rotationswinkel dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Grad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Der Rotationswinkel dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in Grad. |
|

### getText() {#getText--}
```
public final String getText()
```


Liest oder setzt den Text dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - Der Text dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Liest oder setzt den Text dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Text dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Gibt die Sammlung formatierter Textfragmente dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Gibt das Bild dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Setzt das Bild dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | Das Bild dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Gibt den Bezeichner dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück.


**Returns:**
long - Der Bezeichner dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getName() {#getName--}
```
public final String getName()
```


Gibt den Namen dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zurück.


**Returns:**
java.lang.String - Der Name dieses `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Gibt die Sammlung von Hyperlinks zurück, die an diesem `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` angehängt sind.


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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

