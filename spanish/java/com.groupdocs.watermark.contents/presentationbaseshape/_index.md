---
title: "PresentationBaseShape"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona la clase base abstracta para formas de todo tipo en un documento PowerPoint."
type: docs
weight: 77
url: /es/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

Proporciona la clase base abstracta para formas de todo tipo en un documento PowerPoint.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | Obtiene la presentación principal de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Obtiene la configuración del formato de relleno de imagen de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getName()](#getName--) | Obtiene el nombre de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtiene el texto descriptivo (alternativo) asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Establece el texto descriptivo (alternativo) asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getId()](#getId--) | Obtiene el identificador de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | Obtiene la posición de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en el orden Z. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Obtiene el hipervínculo asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Establece el hipervínculo asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` desde el borde izquierdo de la presentación en puntos. |
|
|  | [setX(double value)](#setX-double-) | Establece el desplazamiento horizontal de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` desde el borde izquierdo de la presentación en puntos. |
|
|  | [getY()](#getY--) | Obtiene o establece el desplazamiento vertical de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` desde el borde superior de la presentación en puntos. |
|
|  | [setY(double value)](#setY-double-) | Obtiene o establece el desplazamiento vertical de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` desde el borde superior de la presentación en puntos. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos. |
|
|  | [setWidth(double value)](#setWidth-double-) | Establece el ancho de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos. |
|
|  | [setHeight(double value)](#setHeight-double-) | Establece la altura de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Obtiene la presentación principal de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Obtiene la configuración del formato de relleno de imagen de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - El nombre de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtiene el texto descriptivo (alternativo) asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - El texto descriptivo (alternativo) asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Establece el texto descriptivo (alternativo) asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El texto descriptivo (alternativo) asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Obtiene el identificador de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
long - El identificador de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Obtiene la posición de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en el orden Z.

Una forma con un orden Z mayor siempre está delante de una forma con un orden Z menor.


**Returns:**
int - La posición de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en el orden Z.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Obtiene el hipervínculo asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | actionType | int | La acción que activa el hipervínculo. |
|

**Returns:**
java.lang.String - La URL del hipervínculo que se activa con la acción especificada.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Establece el hipervínculo asociado a este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | actionType | int | La acción que activa el hipervínculo. |
|
|  | url | java.lang.String | La URL del hipervínculo. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtiene el desplazamiento horizontal de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` desde el borde izquierdo de la presentación en puntos.


**Returns:**
double - La coordenada X de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Establece el desplazamiento horizontal de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` desde el borde izquierdo de la presentación en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La coordenada X de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtiene o establece el desplazamiento vertical de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` desde el borde superior de la presentación en puntos.


**Returns:**
double - La coordenada Y de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Obtiene o establece el desplazamiento vertical de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` desde el borde superior de la presentación en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La coordenada y de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene el ancho de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos.


**Returns:**
double - El ancho de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Establece el ancho de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El ancho de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene la altura de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos.


**Returns:**
double - La altura de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Establece la altura de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La altura de este `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en puntos. |
|

