---
title: "DiagramPage"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een pagina van een Visio-document voor."
type: docs
weight: 22
url: /nl/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Stelt een pagina van een Visio-document voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | Haalt de collectie van alle vormen van de pagina op. |
|
|  | [isBackground()](#isBackground--) | Haalt een waarde op die aangeeft of de pagina een achtergrondpagina is. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | Haalt de achtergrondpagina op voor dit . |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van dit op in punten. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van dit op in punten. |
|
|  | [getTopMargin()](#getTopMargin--) | Haalt de grootte van de bovenmarge op in punten. |
|
|  | [getRightMargin()](#getRightMargin--) | Haalt de grootte van de rechtermarge op in punten. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Haalt de grootte van de ondermarge op in punten. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Haalt de grootte van de linkermarge op in punten. |
|
|  | [isVisible()](#isVisible--) | Haalt een waarde op die aangeeft of de pagina zichtbaar is in de UI. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Stelt een waarde in die aangeeft of de pagina zichtbaar is in de UI. |
|
|  | [getName()](#getName--) | Haalt de naam van dit op |
DiagramPage
.
|
|  | [getAsposeDiagramPage()](#getAsposeDiagramPage--) | <br /> |

|
|  | [getContent()](#getContent--) | <br /> |

|
|  | [getPageToDrawingScale()](#getPageToDrawingScale--) | <br /> |

|
|  | [addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-) | <br /> |

|
|  | [convertValueFromDrawingScaleToPageScale(DoubleValue value)](#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getShapes() {#getShapes--}
```
public final DiagramShapeCollection getShapes()
```


Haalt de collectie van alle vormen van de pagina op.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Haalt een waarde op die aangeeft of de pagina een achtergrondpagina is.


**Returns:**
boolean - True als de pagina een achtergrondpagina is; anders, false.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Haalt de achtergrondpagina op voor dit .


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Haalt de breedte van dit op in punten.


**Returns:**
double - De breedte van dit in punten.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Haalt de hoogte van dit op in punten.


**Returns:**
double - De hoogte van dit in punten.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Haalt de grootte van de bovenmarge op in punten.


**Returns:**
double - De grootte van de bovenmarge in punten.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Haalt de grootte van de rechtermarge op in punten.


**Returns:**
double - De grootte van de rechtermarge in punten.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Haalt de grootte van de ondermarge op in punten.


**Returns:**
double - De grootte van de ondermarge in punten.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Haalt de grootte van de linkermarge op in punten.


**Returns:**
double - De grootte van de linkermarge in punten.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Haalt een waarde op die aangeeft of de pagina zichtbaar is in de UI.


**Returns:**
boolean - De waarde die aangeeft of de pagina zichtbaar is in de UI. True als de pagina zichtbaar is; anders, false.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Stelt een waarde in die aangeeft of de pagina zichtbaar is in de UI.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | De waarde die aangeeft of de pagina zichtbaar is in de UI. True als de pagina zichtbaar is; anders, false. |
|

### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van dit op
DiagramPage
.


**Returns:**
java.lang.String - De naam van dit  DiagramPage .

### getAsposeDiagramPage() {#getAsposeDiagramPage--}
```
public final Page getAsposeDiagramPage()
```


<br />



**Returns:**
com.aspose.diagram.Page
### getContent() {#getContent--}
```
public final DiagramContent getContent()
```


<br />



**Returns:**
[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)
### getPageToDrawingScale() {#getPageToDrawingScale--}
```
public final double getPageToDrawingScale()
```


<br />



**Returns:**
double
### addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-}
```
public final void addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
