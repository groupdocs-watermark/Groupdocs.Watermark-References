---
title: "ColorRange"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un rango de colores."
type: docs
weight: 12
url: /es/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Representa un rango de colores. Especifica los rangos usando la representación HSB del color RGB.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | Inicializa una nueva instancia de la clase `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Inicializa una nueva instancia de la clase `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` con un color exacto especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | Obtiene el valor de tono inicial, en grados. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | Establece el valor de tono inicial, en grados. |
|
|  | [getMaxHue()](#getMaxHue--) | Obtiene el valor de tono final, en grados. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | Establece el valor de tono final, en grados. |
|
|  | [getMinSaturation()](#getMinSaturation--) | Obtiene el valor de saturación inicial. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | Establece el valor de saturación inicial. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | Obtiene el valor de saturación final. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | Establece el valor de saturación final. |
|
|  | [getMinBrightness()](#getMinBrightness--) | Obtiene el valor de brillo inicial. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | Establece el valor de brillo inicial. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | Obtiene el valor de brillo final. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | Establece el valor de brillo final. |
|
|  | [isEmpty()](#isEmpty--) | Obtiene un valor que indica si solo el color vacío está dentro del rango. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | Establece un valor que indica si solo el color vacío está dentro del rango. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Inicializa una nueva instancia de la clase `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Inicializa una nueva instancia de la clase `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` con un color exacto especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | El color exacto del cual se crea el rango. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Obtiene el valor de tono inicial, en grados.


**Returns:**
float - El valor inicial del matiz, en grados.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Establece el valor de tono inicial, en grados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | El valor inicial del matiz, en grados. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Obtiene el valor de tono final, en grados.


**Returns:**
float - El valor final del matiz, en grados.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Establece el valor de tono final, en grados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | El valor final del matiz, en grados. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Obtiene el valor de saturación inicial.


**Returns:**
float - La saturación varía de 0.0 a 1.0, donde 0.0 es escala de grises y 1.0 es la máxima saturación.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Establece el valor de saturación inicial.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | La saturación varía de 0.0 a 1.0, donde 0.0 es escala de grises y 1.0 es la máxima saturación. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Obtiene el valor de saturación final.


**Returns:**
float - La saturación varía de 0.0 a 1.0, donde 0.0 es escala de grises y 1.0 es la máxima saturación.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Establece el valor de saturación final.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | La saturación varía de 0.0 a 1.0, donde 0.0 es escala de grises y 1.0 es la máxima saturación. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Obtiene el valor de brillo inicial.


**Returns:**
float - El brillo varía de 0.0 a 1.0, donde 0.0 representa negro y 1.0 representa blanco.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Establece el valor de brillo inicial.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | El brillo varía de 0.0 a 1.0, donde 0.0 representa negro y 1.0 representa blanco. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Obtiene el valor de brillo final.


**Returns:**
float - El brillo varía de 0.0 a 1.0, donde 0.0 representa negro y 1.0 representa blanco.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Establece el valor de brillo final.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | El brillo varía de 0.0 a 1.0, donde 0.0 representa negro y 1.0 representa blanco. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtiene un valor que indica si solo el color vacío está dentro del rango.


**Returns:**
boolean - Verdadero si solo el color vacío está dentro del rango (se ignoran los rangos HSB); de lo contrario, falso.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Establece un valor que indica si solo el color vacío está dentro del rango.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Verdadero si solo el color vacío está dentro del rango (se ignoran los rangos HSB); de lo contrario, falso. |
|

