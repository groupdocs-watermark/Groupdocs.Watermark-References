---
title: "DiagramPage"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une page de document Visio."
type: docs
weight: 22
url: /fr/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Représente une page de document Visio.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | Obtient la collection de toutes les formes de la page. |
|
|  | [isBackground()](#isBackground--) | Obtient une valeur indiquant si la page est une page d'arrière-plan. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | Obtient la page d'arrière-plan pour cet . |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de ceci en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de ceci en points. |
|
|  | [getTopMargin()](#getTopMargin--) | Obtient la taille de la marge supérieure en points. |
|
|  | [getRightMargin()](#getRightMargin--) | Obtient la taille de la marge droite en points. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Obtient la taille de la marge inférieure en points. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Obtient la taille de la marge gauche en points. |
|
|  | [isVisible()](#isVisible--) | Obtient une valeur indiquant si la page est visible dans l'UI. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Définit une valeur indiquant si la page est visible dans l'UI. |
|
|  | [getName()](#getName--) | Obtient le nom de cet |
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


Obtient la collection de toutes les formes de la page.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Obtient une valeur indiquant si la page est une page d'arrière-plan.


**Returns:**
boolean - True si la page est une page d'arrière-plan ; sinon, false.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Obtient la page d'arrière-plan pour cet .


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtient la largeur de ceci en points.


**Returns:**
double - La largeur de ceci en points.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtient la hauteur de ceci en points.


**Returns:**
double - La hauteur de ceci en points.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Obtient la taille de la marge supérieure en points.


**Returns:**
double - La taille de la marge supérieure en points.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Obtient la taille de la marge droite en points.


**Returns:**
double - La taille de la marge droite en points.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Obtient la taille de la marge inférieure en points.


**Returns:**
double - La taille de la marge inférieure en points.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Obtient la taille de la marge gauche en points.


**Returns:**
double - La taille de la marge gauche en points.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Obtient une valeur indiquant si la page est visible dans l'UI.


**Returns:**
boolean - La valeur indiquant si la page est visible dans l'UI. True si la page est visible ; sinon, false.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Définit une valeur indiquant si la page est visible dans l'UI.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | La valeur indiquant si la page est visible dans l'UI. True si la page est visible ; sinon, false. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom de cet
DiagramPage
.


**Returns:**
java.lang.String - Le nom de ce  DiagramPage .

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
| Paramètre | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
