---
title: "SpreadsheetShape"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una forma de dibujo en un documento de Excel."
type: docs
weight: 117
url: /es/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Representa una forma de dibujo en un documento de Excel.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Obtiene la hoja de cálculo principal de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | Obtiene el tipo de forma automática. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | Obtiene el tipo de dibujo mso. |
|
|  | [getText()](#getText--) | Obtiene el texto de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Establece el texto de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtiene la colección de fragmentos de texto formateado de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImage()](#getImage--) | Obtiene la imagen de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Establece la imagen de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Obtiene la configuración del formato de relleno de imagen de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getId()](#getId--) | Obtiene el identificador de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtiene el texto descriptivo (alternativo) asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Establece el texto descriptivo (alternativo) asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [isWordArt()](#isWordArt--) | Obtiene un valor que indica si este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` es un objeto WordArt. |
|
|  | [getName()](#getName--) | Obtiene el nombre de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | Obtiene el hipervínculo asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Establece el hipervínculo asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` desde el borde izquierdo de la hoja de cálculo en puntos. |
|
|  | [setX(double value)](#setX-double-) | Establece el desplazamiento horizontal de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` desde el borde izquierdo de la hoja de cálculo en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` desde el borde superior de la hoja de cálculo en puntos. |
|
|  | [setY(double value)](#setY-double-) | Establece el desplazamiento vertical de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` desde el borde superior de la hoja de cálculo en puntos. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos. |
|
|  | [setWidth(double value)](#setWidth-double-) | Establece el ancho de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos. |
|
|  | [setHeight(double value)](#setHeight-double-) | Establece la altura de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene o establece el ángulo de rotación de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en grados. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Obtiene o establece el ángulo de rotación de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en grados. |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Obtiene la hoja de cálculo principal de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Obtiene el tipo de forma automática.


**Returns:**
int - El tipo de forma automática.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


Obtiene el tipo de dibujo mso.


**Returns:**
int - El tipo de dibujo mso.

### getText() {#getText--}
```
public final String getText()
```


Obtiene el texto de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - El texto de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Establece el texto de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El texto de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtiene la colección de fragmentos de texto formateado de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Obtiene la imagen de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Establece la imagen de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | La imagen de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` o null si la imagen debe eliminarse. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Obtiene la configuración del formato de relleno de imagen de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


Obtiene el identificador de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
int - El identificador de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtiene el texto descriptivo (alternativo) asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - El texto descriptivo (alternativo) asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Establece el texto descriptivo (alternativo) asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El texto descriptivo (alternativo) asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Obtiene un valor que indica si este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` es un objeto WordArt.


**Returns:**
boolean - Verdadero si la forma es un objeto WordArt; de lo contrario, falso.

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - El nombre de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Obtiene el hipervínculo asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - El hipervínculo asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Establece el hipervínculo asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El hipervínculo asociado a este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtiene el desplazamiento horizontal de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` desde el borde izquierdo de la hoja de cálculo en puntos.


**Returns:**
double - La coordenada x de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Establece el desplazamiento horizontal de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` desde el borde izquierdo de la hoja de cálculo en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La coordenada x de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtiene el desplazamiento vertical de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` desde el borde superior de la hoja de cálculo en puntos.


**Returns:**
double - La coordenada y de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Establece el desplazamiento vertical de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` desde el borde superior de la hoja de cálculo en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La coordenada y de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene el ancho de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos.


**Returns:**
double - El ancho de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Establece el ancho de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El ancho de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene la altura de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos.


**Returns:**
double - La altura de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Establece la altura de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La altura de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en puntos. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Obtiene o establece el ángulo de rotación de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en grados.


**Returns:**
double - El ángulo de rotación de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en grados.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Obtiene o establece el ángulo de rotación de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en grados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El ángulo de rotación de este `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en grados. |
|

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

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

