---
title: "DiagramPage"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Visio-Dokumentseite dar."
type: docs
weight: 22
url: /de/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Stellt eine Visio-Dokumentseite dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | Ruft die Sammlung aller Formen der Seite ab. |
|
|  | [isBackground()](#isBackground--) | Ruft einen Wert ab, der angibt, ob die Seite eine Hintergrundseite ist. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | Ruft die Hintergrundseite für dieses . |
|
|  | [getWidth()](#getWidth--) | Ruft die Breite dieses in Punkten ab. |
|
|  | [getHeight()](#getHeight--) | Ruft die Höhe dieses in Punkten ab. |
|
|  | [getTopMargin()](#getTopMargin--) | Gibt die Größe des oberen Randes in Punkten zurück. |
|
|  | [getRightMargin()](#getRightMargin--) | Gibt die Größe des rechten Randes in Punkten zurück. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Gibt die Größe des unteren Randes in Punkten zurück. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Gibt die Größe des linken Randes in Punkten zurück. |
|
|  | [isVisible()](#isVisible--) | Ruft einen Wert ab, der angibt, ob die Seite in der UI sichtbar ist. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Setzt einen Wert, der angibt, ob die Seite in der UI sichtbar ist. |
|
|  | [getName()](#getName--) | Ruft den Namen dieses ab |
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


Ruft die Sammlung aller Formen der Seite ab.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Ruft einen Wert ab, der angibt, ob die Seite eine Hintergrundseite ist.


**Returns:**
boolescher Wert – Wahr, wenn die Seite eine Hintergrundseite ist; andernfalls falsch.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Ruft die Hintergrundseite für dieses .


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ruft die Breite dieses in Punkten ab.


**Returns:**
double – Die Breite dieses in Punkten.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ruft die Höhe dieses in Punkten ab.


**Returns:**
double – Die Höhe dieses in Punkten.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Gibt die Größe des oberen Randes in Punkten zurück.


**Returns:**
double - Die Größe des oberen Randes in Punkten.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Gibt die Größe des rechten Randes in Punkten zurück.


**Returns:**
double - Die Größe des rechten Randes in Punkten.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Gibt die Größe des unteren Randes in Punkten zurück.


**Returns:**
double - Die Größe des unteren Randes in Punkten.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Gibt die Größe des linken Randes in Punkten zurück.


**Returns:**
double - Die Größe des linken Randes in Punkten.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Ruft einen Wert ab, der angibt, ob die Seite in der UI sichtbar ist.


**Returns:**
boolescher Wert – Der Wert, der angibt, ob die Seite in der UI sichtbar ist. Wahr, wenn die Seite sichtbar ist; andernfalls falsch.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Setzt einen Wert, der angibt, ob die Seite in der UI sichtbar ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Der Wert, der angibt, ob die Seite in der UI sichtbar ist. Wahr, wenn die Seite sichtbar ist; andernfalls falsch. |
|

### getName() {#getName--}
```
public final String getName()
```


Ruft den Namen dieses ab
DiagramPage
.


**Returns:**
java.lang.String - Der Name dieser DiagramPage.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
