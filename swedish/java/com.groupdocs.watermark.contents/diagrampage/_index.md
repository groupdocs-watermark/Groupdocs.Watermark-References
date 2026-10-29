---
title: "DiagramPage"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en Visio-dokumentsida."
type: docs
weight: 22
url: /sv/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Representerar en Visio-dokumentsida.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | Hämtar samlingen av alla former på sidan. |
|
|  | [isBackground()](#isBackground--) | Hämtar ett värde som indikerar om sidan är en bakgrundssida. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | Hämtar bakgrundssidan för detta. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta i punkter. |
|
|  | [getTopMargin()](#getTopMargin--) | Hämtar storleken på den övre marginalen i punkter. |
|
|  | [getRightMargin()](#getRightMargin--) | Hämtar storleken på den högra marginalen i punkter. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Hämtar storleken på den nedre marginalen i punkter. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Hämtar storleken på den vänstra marginalen i punkter. |
|
|  | [isVisible()](#isVisible--) | Hämtar ett värde som indikerar om sidan är synlig i UI. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Ställer in ett värde som indikerar om sidan är synlig i UI. |
|
|  | [getName()](#getName--) | Hämtar namnet på detta |
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


Hämtar samlingen av alla former på sidan.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Hämtar ett värde som indikerar om sidan är en bakgrundssida.


**Returns:**
boolean - Sant om sidan är en bakgrundssida; annars falskt.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Hämtar bakgrundssidan för detta.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Hämtar bredden på detta i punkter.


**Returns:**
double - Bredden på detta i punkter.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Hämtar höjden på detta i punkter.


**Returns:**
double - Höjden på detta i punkter.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Hämtar storleken på den övre marginalen i punkter.


**Returns:**
double - Storleken på den övre marginalen i punkter.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Hämtar storleken på den högra marginalen i punkter.


**Returns:**
double - Storleken på den högra marginalen i punkter.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Hämtar storleken på den nedre marginalen i punkter.


**Returns:**
double - Storleken på den nedre marginalen i punkter.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Hämtar storleken på den vänstra marginalen i punkter.


**Returns:**
double - Storleken på den vänstra marginalen i punkter.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Hämtar ett värde som indikerar om sidan är synlig i UI.


**Returns:**
boolean - Värdet som indikerar om sidan är synlig i UI. Sant om sidan är synlig; annars falskt.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Ställer in ett värde som indikerar om sidan är synlig i UI.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Värdet som indikerar om sidan är synlig i UI. Sant om sidan är synlig; annars falskt. |
|

### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på detta
DiagramPage
.


**Returns:**
java.lang.String - Namnet på detta DiagramPage.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
