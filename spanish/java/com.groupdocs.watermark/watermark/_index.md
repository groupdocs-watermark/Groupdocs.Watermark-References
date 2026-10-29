---
title: "Watermark"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una marca de agua que se añadirá a un documento."
type: docs
weight: 13
url: /es/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Representa una marca de agua que se añadirá a un documento.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | Obtiene o establece la opacidad de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Obtiene o establece la opacidad de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getY()](#getY--) | Obtiene la coordenada y de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setY(double value)](#setY-double-) | Establece la coordenada y de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getX()](#getX--) | Obtiene la coordenada x de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setX(double value)](#setX-double-) | Establece la coordenada x de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Obtiene la alineación vertical de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Establece la alineación vertical de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Obtiene la alineación horizontal de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Establece la alineación horizontal de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de este `[Watermark](../../com.groupdocs.watermark/watermark)` en grados. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Establece el ángulo de rotación de este `[Watermark](../../com.groupdocs.watermark/watermark)` en grados. |
|
|  | [isBackground()](#isBackground--) | Obtiene un valor que indica si la marca de agua debe colocarse en el fondo. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Establece un valor que indica si la marca de agua debe colocarse en el fondo. |
|
|  | [getMargins()](#getMargins--) | Obtiene la configuración de márgenes de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Establece la configuración de márgenes de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Obtiene la configuración de páginas de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | Establece los ajustes de configuración de páginas de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura deseada de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHeight(double value)](#setHeight-double-) | Establece la altura deseada de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho deseado de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setWidth(double value)](#setWidth-double-) | Establece el ancho deseado de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getScaleFactor()](#getScaleFactor--) | Obtiene un valor que define cómo el tamaño de la marca de agua depende del tamaño del elemento padre. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | Establece un valor que define cómo el tamaño de la marca de agua depende del tamaño del elemento padre. |
|
|  | [getSizingType()](#getSizingType--) | Obtiene un valor que especifica la forma en que la marca de agua debe dimensionarse. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | Establece un valor que especifica la forma en que la marca de agua debe dimensionarse. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | Obtiene un valor que indica si el tamaño y las coordenadas de la marca de agua se calculan |
considerando los márgenes del elemento padre.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Establece un valor que indica si el tamaño y las coordenadas de la marca de agua se calculan |
considerando los márgenes del elemento padre.
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getTransparency()](#getTransparency--) |  |
| [getSize()](#getSize--) |  |
| [getTileOptions()](#getTileOptions--) |  |
| [setTileOptions(TileOptions tileOptions)](#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-) |  |
| [copyPropertiesValues(Watermark source, Watermark destination)](#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```




### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Obtiene o establece la opacidad de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

El valor de opacidad debe estar entre 0 y 1. El valor predeterminado es 1.


**Returns:**
double - La opacidad de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Obtiene o establece la opacidad de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

El valor de opacidad debe estar entre 0 y 1. El valor predeterminado es 1.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La opacidad de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtiene la coordenada y de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La coordenada y de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Establece la coordenada y de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La coordenada y de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtiene la coordenada x de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La coordenada x de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Establece la coordenada x de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La coordenada x de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Obtiene la alineación vertical de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

El valor predeterminado es `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - El `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Establece la alineación vertical de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

El valor predeterminado es `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | int | El `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Obtiene la alineación horizontal de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

El valor predeterminado es `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - El `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Establece la alineación horizontal de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

El valor predeterminado es `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | int | El `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Obtiene el ángulo de rotación de este `[Watermark](../../com.groupdocs.watermark/watermark)` en grados.


**Returns:**
double - El ángulo de rotación de este `[Watermark](../../com.groupdocs.watermark/watermark)` en grados.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Establece el ángulo de rotación de este `[Watermark](../../com.groupdocs.watermark/watermark)` en grados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El ángulo de rotación de este `[Watermark](../../com.groupdocs.watermark/watermark)` en grados. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Obtiene un valor que indica si la marca de agua debe colocarse en el fondo.


**Returns:**
boolean - Si el valor es verdadero, la marca de agua se colocará en la parte inferior. Por defecto, el valor es falso, la marca de agua se colocará en la parte superior.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Establece un valor que indica si la marca de agua debe colocarse en el fondo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Si el valor es verdadero, la marca de agua se colocará en la parte inferior. Por defecto, el valor es falso, la marca de agua se colocará en la parte superior. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Obtiene la configuración de márgenes de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Establece la configuración de márgenes de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | Los ajustes de margen de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Obtiene la configuración de páginas de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Establece los ajustes de configuración de páginas de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Los ajustes de configuración de páginas de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene la altura deseada de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La altura deseada de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Establece la altura deseada de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

Establecer esta propiedad también cambiará el valor de `#getSizingType().getSizingType()`
propiedad a `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | La altura deseada de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene el ancho deseado de este `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - El ancho deseado de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Establece el ancho deseado de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

Establecer esta propiedad también cambiará el valor de `#getSizingType().getSizingType()`
propiedad a `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El ancho deseado de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Obtiene un valor que define cómo el tamaño de la marca de agua depende del tamaño del elemento padre.

El valor debe estar entre 0 y 1.


**Returns:**
double - El factor de escala de este `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Establece un valor que define cómo el tamaño de la marca de agua depende del tamaño del elemento padre.

El valor debe estar entre 0 y 1.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | double | El factor de escala de este `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Obtiene un valor que especifica la forma en que la marca de agua debe dimensionarse.


**Returns:**
int - El tipo de dimensionado.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Establece un valor que especifica la forma en que la marca de agua debe dimensionarse.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El tipo de dimensionado. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Obtiene un valor que indica si el tamaño y las coordenadas de la marca de agua se calculan
considerando los márgenes del elemento padre.


**Returns:**
boolean - Si el valor es verdadero, el tamaño y las coordenadas de la marca de agua se calculan considerando los márgenes del contenedor. Por defecto, el valor es falso, los márgenes del contenedor se ignoran.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Establece un valor que indica si el tamaño y las coordenadas de la marca de agua se calculan
considerando los márgenes del elemento padre.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Si el valor es verdadero, el tamaño y las coordenadas de la marca de agua se calculan considerando los márgenes del contenedor. Por defecto, el valor es falso, los márgenes del contenedor se ignoran. |
|

### isImageWatermark() {#isImageWatermark--}
```
public abstract boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public abstract boolean isTextWatermark()
```




**Returns:**
boolean
### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getSize() {#getSize--}
```
public abstract SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getTileOptions() {#getTileOptions--}
```
public TileOptions getTileOptions()
```




**Returns:**
[TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions)
### setTileOptions(TileOptions tileOptions) {#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-}
```
public void setTileOptions(TileOptions tileOptions)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| destination | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### deepClone() {#deepClone--}
```
public abstract Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
