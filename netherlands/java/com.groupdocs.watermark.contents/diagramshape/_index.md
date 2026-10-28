---
title: "DiagramShape"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een tekenvorm voor in een Visio-document."
type: docs
weight: 24
url: /nl/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Stelt een tekenvorm voor in een Visio-document.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | Haalt de bovenliggende pagina op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten. |
|
|  | [setWidth(double value)](#setWidth-double-) | Stelt de breedte in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten. |
|
|  | [setHeight(double value)](#setHeight-double-) | Stelt de hoogte in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten. |
|
|  | [getX()](#getX--) | Haalt de horizontale offset op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de linkerrand van de pagina in punten. |
|
|  | [setX(double value)](#setX-double-) | Stelt de horizontale offset in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de linkerrand van de pagina in punten. |
|
|  | [getY()](#getY--) | Haalt de verticale offset op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de onderrand van de pagina in punten. |
|
|  | [setY(double value)](#setY-double-) | Stelt de verticale offset in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de onderrand van de pagina in punten. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt op of stelt de rotatiehoek van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in graden in. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Haalt op of stelt de rotatiehoek van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in graden in. |
|
|  | [getText()](#getText--) | Haalt op of stelt de tekst van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Haalt op of stelt de tekst van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Haalt de collectie van opgemaakte tekstfragmenten op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getImage()](#getImage--) | Haalt de afbeelding op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Stelt de afbeelding in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getId()](#getId--) | Haalt de identificatie op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getName()](#getName--) | Haalt de naam op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getHyperlinks()](#getHyperlinks--) | Haalt de collectie van hyperlinks op die aan dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zijn gekoppeld. |
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


Haalt de bovenliggende pagina op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Haalt de breedte op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten.


**Returns:**
double - De breedte van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Stelt de breedte in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De breedte van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Haalt de hoogte op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten.


**Returns:**
double - De hoogte van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Stelt de hoogte in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De hoogte van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in punten. |
|

### getX() {#getX--}
```
public final double getX()
```


Haalt de horizontale offset op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de linkerrand van de pagina in punten.


**Returns:**
double - De horizontale offset van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de linkerrand van de pagina in punten.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Stelt de horizontale offset in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de linkerrand van de pagina in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De horizontale offset van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de linkerrand van de pagina in punten. |
|

### getY() {#getY--}
```
public final double getY()
```


Haalt de verticale offset op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de onderrand van de pagina in punten.


**Returns:**
double - De verticale offset van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de onderrand van de pagina in punten.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Stelt de verticale offset in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de onderrand van de pagina in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De verticale offset van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` vanaf de onderrand van de pagina in punten. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Haalt op of stelt de rotatiehoek van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in graden in.


**Returns:**
double - De rotatiehoek van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in graden.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Haalt op of stelt de rotatiehoek van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in graden in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De rotatiehoek van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in graden. |
|

### getText() {#getText--}
```
public final String getText()
```


Haalt op of stelt de tekst van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in.


**Returns:**
java.lang.String - De tekst van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Haalt op of stelt de tekst van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De tekst van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Haalt de collectie van opgemaakte tekstfragmenten op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Haalt de afbeelding op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Stelt de afbeelding in van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | De afbeelding van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Haalt de identificatie op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
long - De identifier van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getName() {#getName--}
```
public final String getName()
```


Haalt de naam op van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - De naam van dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Haalt de collectie van hyperlinks op die aan dit `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` zijn gekoppeld.


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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

