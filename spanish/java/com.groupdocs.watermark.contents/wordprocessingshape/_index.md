---
title: "WordProcessingShape"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una forma de dibujo en un documento Word."
type: docs
weight: 141
url: /es/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Representa una forma de dibujo en un documento Word.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSection()](#getSection--) | Obtiene la sección padre de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Obtiene el encabezado/pie de página padre de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (si está presente). |
|
|  | [getShapeType()](#getShapeType--) | Obtiene el tipo de forma. |
|
|  | [isWordArt()](#isWordArt--) | Obtiene un valor que indica si este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` es un objeto WordArt. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtiene el texto descriptivo (alternativo) asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Establece el texto descriptivo (alternativo) asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getName()](#getName--) | Obtiene el nombre de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getBehindText()](#getBehindText--) | Obtiene un valor que indica si la forma está delante o detrás del texto. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | Establece un valor que indica si la forma está delante o detrás del texto. |
|
|  | [getText()](#getText--) | Obtiene el texto de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Establece el texto de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtiene la colección de fragmentos de texto formateado de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getImage()](#getImage--) | Obtiene la imagen de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Establece la imagen de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Obtiene un valor que especifica cómo se posiciona horizontalmente la forma. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Obtiene un valor que especifica cómo se posiciona verticalmente la forma. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Obtiene un valor que especifica respecto a qué se posiciona horizontalmente la forma. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Obtiene un valor que especifica respecto a qué se posiciona verticalmente la forma. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | Obtiene el hipervínculo asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Establece el hipervínculo asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos. |
|
|  | [setWidth(double value)](#setWidth-double-) | Establece el ancho de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos. |
|
|  | [setHeight(double value)](#setHeight-double-) | Establece la altura de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en grados. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Establece el ángulo de rotación de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en grados. |
|
|  | [getX()](#getX--) | Obtiene o establece el desplazamiento horizontal de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` desde el borde izquierdo de la página en puntos. |
|
|  | [setX(double value)](#setX-double-) | Obtiene o establece el desplazamiento horizontal de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` desde el borde izquierdo de la página en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` desde el borde superior de la página en puntos. |
|
|  | [setY(double value)](#setY-double-) | Establece el desplazamiento vertical de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` desde el borde superior de la página en puntos. |
|
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


Obtiene la sección padre de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Obtiene el encabezado/pie de página padre de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (si está presente).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Obtiene el tipo de forma.


**Returns:**
int - El tipo de forma.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Obtiene un valor que indica si este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` es un objeto WordArt.


**Returns:**
boolean - Verdadero si la forma es un objeto WordArt; de lo contrario, falso.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtiene el texto descriptivo (alternativo) asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - El texto descriptivo (alternativo) asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Establece el texto descriptivo (alternativo) asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El texto descriptivo (alternativo) asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - El nombre de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Obtiene un valor que indica si la forma está delante o detrás del texto.


**Returns:**
boolean - El valor que indica si la forma está sobre o detrás del texto. Verdadero si la forma está detrás del texto; de lo contrario, falso.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Establece un valor que indica si la forma está delante o detrás del texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | El valor que indica si la forma está sobre o detrás del texto. Verdadero si la forma está detrás del texto; de lo contrario, falso. |
|

### getText() {#getText--}
```
public final String getText()
```


Obtiene el texto de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - El texto de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Establece el texto de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El texto de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtiene la colección de fragmentos de texto formateado de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Obtiene la imagen de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Establece la imagen de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | La imagen de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` o `null` si la imagen debe eliminarse. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Obtiene un valor que especifica cómo se posiciona horizontalmente la forma.


**Returns:**
int - El valor de alineación horizontal.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Obtiene un valor que especifica cómo se posiciona verticalmente la forma.


**Returns:**
int - El valor de alineación vertical.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Obtiene un valor que especifica respecto a qué se posiciona horizontalmente la forma.


**Returns:**
int - El valor de posición horizontal relativa.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Obtiene un valor que especifica respecto a qué se posiciona verticalmente la forma.


**Returns:**
int - El valor de posición vertical relativa.

### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Obtiene el hipervínculo asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - El hipervínculo asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Establece el hipervínculo asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El hipervínculo asociado a este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene el ancho de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos.


**Returns:**
double - El ancho de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Establece el ancho de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El ancho de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene la altura de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos.


**Returns:**
double - La altura de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Establece la altura de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La altura de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en puntos. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Obtiene el ángulo de rotación de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en grados.


**Returns:**
double - El ángulo de rotación de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en grados.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Establece el ángulo de rotación de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en grados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El ángulo de rotación de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en grados. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtiene o establece el desplazamiento horizontal de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` desde el borde izquierdo de la página en puntos.


**Returns:**
double - La coordenada x de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Obtiene o establece el desplazamiento horizontal de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` desde el borde izquierdo de la página en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La coordenada x de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtiene el desplazamiento vertical de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` desde el borde superior de la página en puntos.


**Returns:**
double - La coordenada y de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Establece el desplazamiento vertical de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` desde el borde superior de la página en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La coordenada y de este `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageData | byte[] |  |

