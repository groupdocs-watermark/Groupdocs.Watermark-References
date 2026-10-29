---
title: "OfficeLineFormat"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un formato de línea de forma."
type: docs
weight: 47
url: /es/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Representa un formato de línea de forma.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | Inicializa una nueva instancia de la clase `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWeight()](#getWeight--) | Obtiene el grosor del pincel que traza la ruta de una forma. |
|
|  | [setWeight(double value)](#setWeight-double-) | Establece el grosor del pincel que traza la ruta de una forma. |
|
|  | [getColor()](#getColor--) | Obtiene el color de la línea. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Establece el color de la línea. |
|
|  | [getOpacity()](#getOpacity--) | Obtiene la opacidad de la línea. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Establece la opacidad de la línea. |
|
|  | [getEnabled()](#getEnabled--) | Obtiene un valor que indica si una forma será trazada. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | Establece un valor que indica si una forma será trazada. |
|
|  | [getDashStyle()](#getDashStyle--) | Obtiene el patrón de puntos y guiones para una línea. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Establece el patrón de puntos y guiones para una línea. |
|
|  | [getLineStyle()](#getLineStyle--) | Obtiene el estilo de la línea. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | Establece el estilo de la línea. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Inicializa una nueva instancia de la clase `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


Obtiene el grosor del pincel que traza la ruta de una forma.


**Returns:**
double - El grosor de la línea en puntos. El valor predeterminado es 0.75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Establece el grosor del pincel que traza la ruta de una forma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | El grosor de la línea en puntos. El valor predeterminado es 0.75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Obtiene el color de la línea.

El valor predeterminado es `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Establece el color de la línea.

El valor predeterminado es `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | El color de la línea. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Obtiene la opacidad de la línea.


**Returns:**
double - El valor debe estar entre 0 y 1. El valor predeterminado es 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Establece la opacidad de la línea.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | El valor debe estar entre 0 y 1. El valor predeterminado es 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Obtiene un valor que indica si una forma será trazada.


**Returns:**
boolean - El valor predeterminado es false.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Establece un valor que indica si una forma será trazada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | El valor predeterminado es false. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Obtiene el patrón de puntos y guiones para una línea.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Establece el patrón de puntos y guiones para una línea.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Obtiene el estilo de la línea.

El valor predeterminado es `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Returns:**
int - El estilo de línea.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Establece el estilo de la línea.

El valor predeterminado es `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El estilo de línea. |
|

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


<br />



**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```


<br />



**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
