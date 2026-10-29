---
title: "DiagramPage"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una página de documento Visio."
type: docs
weight: 22
url: /es/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Representa una página de documento Visio.

## Métodos

| Método | Descripción |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | Obtiene la colección de todas las formas de la página. |
|
|  | [isBackground()](#isBackground--) | Obtiene un valor que indica si la página es una página de fondo. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | Obtiene la página de fondo para este . |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de esto en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de esto en puntos. |
|
|  | [getTopMargin()](#getTopMargin--) | Obtiene el tamaño del margen superior en puntos. |
|
|  | [getRightMargin()](#getRightMargin--) | Obtiene el tamaño del margen derecho en puntos. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Obtiene el tamaño del margen inferior en puntos. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Obtiene el tamaño del margen izquierdo en puntos. |
|
|  | [isVisible()](#isVisible--) | Obtiene un valor que indica si la página es visible en la UI. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Establece un valor que indica si la página es visible en la UI. |
|
|  | [getName()](#getName--) | Obtiene el nombre de este |
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


Obtiene la colección de todas las formas de la página.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Obtiene un valor que indica si la página es una página de fondo.


**Returns:**
boolean - Verdadero si la página es una página de fondo; de lo contrario, falso.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Obtiene la página de fondo para este .


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene el ancho de esto en puntos.


**Returns:**
double - El ancho de esto en puntos.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene la altura de esto en puntos.


**Returns:**
double - La altura de esto en puntos.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Obtiene el tamaño del margen superior en puntos.


**Returns:**
double - El tamaño del margen superior en puntos.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Obtiene el tamaño del margen derecho en puntos.


**Returns:**
double - El tamaño del margen derecho en puntos.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Obtiene el tamaño del margen inferior en puntos.


**Returns:**
double - El tamaño del margen inferior en puntos.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Obtiene el tamaño del margen izquierdo en puntos.


**Returns:**
double - El tamaño del margen izquierdo en puntos.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Obtiene un valor que indica si la página es visible en la UI.


**Returns:**
boolean - El valor que indica si la página es visible en la UI. Verdadero si la página es visible; de lo contrario, falso.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Establece un valor que indica si la página es visible en la UI.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | El valor que indica si la página es visible en la UI. Verdadero si la página es visible; de lo contrario, falso. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de este
DiagramPage
.


**Returns:**
java.lang.String - El nombre de este  DiagramPage .

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
