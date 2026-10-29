---
title: "Margins"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa la configuración de márgenes para cada borde de un objeto."
type: docs
weight: 15
url: /es/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Representa la configuración de márgenes para cada borde de un objeto.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Margins()](#Margins--) | Inicializa una nueva instancia de la clase `[Margins](../../com.groupdocs.watermark.watermarks/margins)`. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Inicializa una nueva instancia de la clase `[Margins](../../com.groupdocs.watermark.watermarks/margins)` con el tipo, ubicación y tamaño especificados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | Obtiene `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | Establece `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [getLeft()](#getLeft--) | Obtiene el margen izquierdo. |
|
|  | [setLeft(double value)](#setLeft-double-) | Establece el margen izquierdo. |
|
|  | [getRight()](#getRight--) | Obtiene el margen derecho. |
|
|  | [setRight(double value)](#setRight-double-) | Establece el margen derecho. |
|
|  | [getTop()](#getTop--) | Obtiene el margen superior. |
|
|  | [setTop(double value)](#setTop-double-) | Establece el margen superior. |
|
|  | [getBottom()](#getBottom--) | Obtiene el margen inferior. |
|
|  | [setBottom(double value)](#setBottom-double-) | Establece el margen inferior. |
|
### Margins() {#Margins--}
```
public Margins()
```


Inicializa una nueva instancia de la clase `[Margins](../../com.groupdocs.watermark.watermarks/margins)`.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Inicializa una nueva instancia de la clase `[Margins](../../com.groupdocs.watermark.watermarks/margins)` con el tipo, ubicación y tamaño especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | marginType | int | El `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Especifica cómo deben interpretarse los valores de margen. |
|
|  | izquierda | double | El valor del margen izquierdo. |
|
|  | derecha | double | El valor del margen derecho. |
|
|  | superior | double | El valor del margen superior. |
|
|  | inferior | double | El valor del margen inferior. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Obtiene `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Establecer un nuevo valor a esta propiedad restablece automáticamente todos los márgenes a sus valores predeterminados (cero).

El valor predeterminado es `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - El valor que especifica cómo deben interpretarse los márgenes.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Establece `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Establecer un nuevo valor a esta propiedad restablece automáticamente todos los márgenes a sus valores predeterminados (cero).

El valor predeterminado es `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El valor que especifica cómo deben interpretarse los márgenes. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Obtiene el margen izquierdo.


**Returns:**
double - Desplazamiento horizontal desde el borde izquierdo del elemento padre.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Establece el margen izquierdo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | Desplazamiento horizontal desde el borde izquierdo del padre. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


Obtiene el margen derecho.


**Returns:**
double - Desplazamiento horizontal desde el borde derecho del padre.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Establece el margen derecho.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | Desplazamiento horizontal desde el borde derecho del padre. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


Obtiene el margen superior.


**Returns:**
double - Desplazamiento horizontal desde el borde superior del padre.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Establece el margen superior.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | Desplazamiento horizontal desde el borde superior del padre. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Obtiene el margen inferior.


**Returns:**
double - Desplazamiento horizontal desde el borde inferior del padre.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Establece el margen inferior.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | Desplazamiento horizontal desde el borde inferior del padre. |
|

