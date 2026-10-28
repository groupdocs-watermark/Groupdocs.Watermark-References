---
title: "DiagramShape"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une forme de dessin dans un document Visio."
type: docs
weight: 24
url: /fr/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Représente une forme de dessin dans un document Visio.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | Obtient la page parente de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points. |
|
|  | [setWidth(double value)](#setWidth-double-) | Définit la largeur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points. |
|
|  | [setHeight(double value)](#setHeight-double-) | Définit la hauteur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points. |
|
|  | [getX()](#getX--) | Obtient le décalage horizontal de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure gauche de la page en points. |
|
|  | [setX(double value)](#setX-double-) | Définit le décalage horizontal de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure gauche de la page en points. |
|
|  | [getY()](#getY--) | Obtient le décalage vertical de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure inférieure de la page en points. |
|
|  | [setY(double value)](#setY-double-) | Définit le décalage vertical de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure inférieure de la page en points. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient ou définit l'angle de rotation de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en degrés. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Obtient ou définit l'angle de rotation de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en degrés. |
|
|  | [getText()](#getText--) | Obtient ou définit le texte de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtient la collection de fragments de texte formatés de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getImage()](#getImage--) | Obtient l'image de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Définit l'image de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getId()](#getId--) | Obtient l'identifiant de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getName()](#getName--) | Obtient le nom de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getHyperlinks()](#getHyperlinks--) | Obtient la collection de liens hypertexte attachés à ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
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


Obtient la page parente de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtient la largeur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points.


**Returns:**
double - La largeur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Définit la largeur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La largeur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtient la hauteur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points.


**Returns:**
double - La hauteur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Définit la hauteur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La hauteur de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en points. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtient le décalage horizontal de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure gauche de la page en points.


**Returns:**
double - Le décalage horizontal de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure gauche de la page en points.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Définit le décalage horizontal de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure gauche de la page en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | Le décalage horizontal de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure gauche de la page en points. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtient le décalage vertical de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure inférieure de la page en points.


**Returns:**
double - Le décalage vertical de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure inférieure de la page en points.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Définit le décalage vertical de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure inférieure de la page en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | Le décalage vertical de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` depuis la bordure inférieure de la page en points. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Obtient ou définit l'angle de rotation de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en degrés.


**Returns:**
double - L'angle de rotation de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en degrés.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Obtient ou définit l'angle de rotation de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en degrés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | L'angle de rotation de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en degrés. |
|

### getText() {#getText--}
```
public final String getText()
```


Obtient ou définit le texte de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - Le texte de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Obtient ou définit le texte de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtient la collection de fragments de texte formatés de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Obtient l'image de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Définit l'image de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | L'image de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Obtient l'identifiant de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
long - L'identifiant de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - Le nom de ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Obtient la collection de liens hypertexte attachés à ce `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

