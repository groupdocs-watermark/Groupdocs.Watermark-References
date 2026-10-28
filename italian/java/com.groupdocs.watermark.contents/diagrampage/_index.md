---
title: "DiagramPage"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una pagina di documento Visio."
type: docs
weight: 22
url: /it/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Rappresenta una pagina di documento Visio.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | Ottiene la collezione di tutte le forme della pagina. |
|
|  | [isBackground()](#isBackground--) | Ottiene un valore che indica se la pagina è una pagina di sfondo. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | Ottiene la pagina di sfondo per questo. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo in punti. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo in punti. |
|
|  | [getTopMargin()](#getTopMargin--) | Ottiene la dimensione del margine superiore in punti. |
|
|  | [getRightMargin()](#getRightMargin--) | Ottiene la dimensione del margine destro in punti. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Ottiene la dimensione del margine inferiore in punti. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Ottiene la dimensione del margine sinistro in punti. |
|
|  | [isVisible()](#isVisible--) | Ottiene un valore che indica se la pagina è visibile nell'interfaccia utente. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Imposta un valore che indica se la pagina è visibile nell'interfaccia utente. |
|
|  | [getName()](#getName--) | Ottiene il nome di questo |
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


Ottiene la collezione di tutte le forme della pagina.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Ottiene un valore che indica se la pagina è una pagina di sfondo.


**Returns:**
boolean - Vero se la pagina è una pagina di sfondo; altrimenti, falso.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Ottiene la pagina di sfondo per questo.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ottiene la larghezza di questo in punti.


**Returns:**
double - La larghezza di questo in punti.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ottiene l'altezza di questo in punti.


**Returns:**
double - L'altezza di questo in punti.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Ottiene la dimensione del margine superiore in punti.


**Returns:**
double - La dimensione del margine superiore in punti.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Ottiene la dimensione del margine destro in punti.


**Returns:**
double - La dimensione del margine destro in punti.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Ottiene la dimensione del margine inferiore in punti.


**Returns:**
double - La dimensione del margine inferiore in punti.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Ottiene la dimensione del margine sinistro in punti.


**Returns:**
double - La dimensione del margine sinistro in punti.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Ottiene un valore che indica se la pagina è visibile nell'interfaccia utente.


**Returns:**
boolean - Il valore che indica se la pagina è visibile nell'interfaccia utente. Vero se la pagina è visibile; altrimenti, falso.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Imposta un valore che indica se la pagina è visibile nell'interfaccia utente.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Il valore che indica se la pagina è visibile nell'interfaccia utente. Vero se la pagina è visibile; altrimenti, falso. |
|

### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome di questo
DiagramPage
.


**Returns:**
java.lang.String - Il nome di questo  DiagramPage .

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
