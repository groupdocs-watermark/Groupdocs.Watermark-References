---
title: "DiagramShape"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una forma de dibujo en un documento Visio."
type: docs
weight: 24
url: /es/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Representa una forma de dibujo en un documento Visio.

## Métodos

| Método | Descripción |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | Obtiene la página padre de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos. |
|
|  | [setWidth(double value)](#setWidth-double-) | Establece el ancho de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos. |
|
|  | [setHeight(double value)](#setHeight-double-) | Establece la altura de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos. |
|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde izquierdo de la página en puntos. |
|
|  | [setX(double value)](#setX-double-) | Establece el desplazamiento horizontal de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde izquierdo de la página en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde inferior de la página en puntos. |
|
|  | [setY(double value)](#setY-double-) | Establece el desplazamiento vertical de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde inferior de la página en puntos. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene o establece el ángulo de rotación de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en grados. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Obtiene o establece el ángulo de rotación de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en grados. |
|
|  | [getText()](#getText--) | Obtiene o establece el texto de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtiene la colección de fragmentos de texto formateado de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getImage()](#getImage--) | Obtiene la imagen de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Establece la imagen de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getId()](#getId--) | Obtiene el identificador de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getName()](#getName--) | Obtiene el nombre de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getHyperlinks()](#getHyperlinks--) | Obtiene la colección de hipervínculos adjuntos a este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
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


Obtiene la página padre de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene el ancho de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos.


**Returns:**
double - El ancho de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Establece el ancho de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El ancho de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene la altura de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos.


**Returns:**
double - La altura de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Establece la altura de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La altura de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en puntos. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtiene el desplazamiento horizontal de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde izquierdo de la página en puntos.


**Returns:**
double - El desplazamiento horizontal de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde izquierdo de la página en puntos.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Establece el desplazamiento horizontal de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde izquierdo de la página en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El desplazamiento horizontal de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde izquierdo de la página en puntos. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtiene el desplazamiento vertical de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde inferior de la página en puntos.


**Returns:**
double - El desplazamiento vertical de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde inferior de la página en puntos.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Establece el desplazamiento vertical de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde inferior de la página en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El desplazamiento vertical de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` desde el borde inferior de la página en puntos. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Obtiene o establece el ángulo de rotación de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en grados.


**Returns:**
double - El ángulo de rotación de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en grados.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Obtiene o establece el ángulo de rotación de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en grados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El ángulo de rotación de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` en grados. |
|

### getText() {#getText--}
```
public final String getText()
```


Obtiene o establece el texto de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - El texto de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Obtiene o establece el texto de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El texto de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtiene la colección de fragmentos de texto formateado de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Obtiene la imagen de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Establece la imagen de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | La imagen de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Obtiene el identificador de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
long - El identificador de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - El nombre de este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Obtiene la colección de hipervínculos adjuntos a este `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

