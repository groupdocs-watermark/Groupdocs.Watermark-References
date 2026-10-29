---
title: "DiagramShape"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en ritningsform i ett Visio-dokument."
type: docs
weight: 24
url: /sv/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Representerar en ritningsform i ett Visio-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | Hämtar föräldrasidan för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ställer in bredden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ställer in höjden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter. |
|
|  | [getX()](#getX--) | Hämtar den horisontella förskjutningen för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans vänstra kant i punkter. |
|
|  | [setX(double value)](#setX-double-) | Ställer in den horisontella förskjutningen för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans vänstra kant i punkter. |
|
|  | [getY()](#getY--) | Hämtar den vertikala förskjutningen för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans nedre kant i punkter. |
|
|  | [setY(double value)](#setY-double-) | Ställer in den vertikala förskjutningen för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans nedre kant i punkter. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar eller anger rotationsvinkeln för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i grader. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Hämtar eller anger rotationsvinkeln för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i grader. |
|
|  | [getText()](#getText--) | Hämtar eller anger texten för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger texten för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Hämtar samlingen av formaterade textfragment för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getImage()](#getImage--) | Hämtar bilden för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Ställer in bilden för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getId()](#getId--) | Hämtar identifieraren för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getName()](#getName--) | Hämtar namnet på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getHyperlinks()](#getHyperlinks--) | Hämtar samlingen av hyperlänkar som är bifogade till detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
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


Hämtar föräldrasidan för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Hämtar bredden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter.


**Returns:**
double - Bredden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ställer in bredden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Bredden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Hämtar höjden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter.


**Returns:**
double - Höjden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ställer in höjden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Höjden på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i punkter. |
|

### getX() {#getX--}
```
public final double getX()
```


Hämtar den horisontella förskjutningen för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans vänstra kant i punkter.


**Returns:**
double - Den horisontella förskjutningen av detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans vänstra kant i punkter.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ställer in den horisontella förskjutningen för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans vänstra kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Den horisontella förskjutningen av detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans vänstra kant i punkter. |
|

### getY() {#getY--}
```
public final double getY()
```


Hämtar den vertikala förskjutningen för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans nedre kant i punkter.


**Returns:**
double - Den vertikala förskjutningen av detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans nedre kant i punkter.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ställer in den vertikala förskjutningen för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans nedre kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Den vertikala förskjutningen av detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` från sidans nedre kant i punkter. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Hämtar eller anger rotationsvinkeln för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i grader.


**Returns:**
double - Rotationsvinkeln för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i grader.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Hämtar eller anger rotationsvinkeln för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i grader.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Rotationsvinkeln för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` i grader. |
|

### getText() {#getText--}
```
public final String getText()
```


Hämtar eller anger texten för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - Texten för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Hämtar eller anger texten för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Texten för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Hämtar samlingen av formaterade textfragment för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Hämtar bilden för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Ställer in bilden för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | Bilden för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Hämtar identifieraren för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
long - Identifieraren för detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - Namnet på detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Hämtar samlingen av hyperlänkar som är bifogade till detta `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

