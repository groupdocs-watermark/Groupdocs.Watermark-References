---
title: "OfficeImageEffects"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa efectos que se pueden aplicar a una marca de agua de imagen para un contenido de oficina."
type: docs
weight: 45
url: /es/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

Representa efectos que se pueden aplicar a una marca de agua de imagen para un contenido de oficina.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | Obtiene una configuración de formato de línea para el borde de la imagen. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | Establece una configuración de formato de línea para el borde de la imagen. |
|
|  | [getGrayScale()](#getGrayScale--) | Obtiene un valor que indica si una imagen se mostrará en modo escala de grises. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | Establece un valor que indica si una imagen se mostrará en modo escala de grises. |
|
|  | [getChromaKey()](#getChromaKey--) | Obtiene el valor de color de la imagen que se tratará como transparente. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | Establece el valor de color de la imagen que se tratará como transparente. |
|
|  | [getBrightness()](#getBrightness--) | Obtiene el brillo de la imagen. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | Establece el brillo de la imagen. |
|
|  | [getContrast()](#getContrast--) | Obtiene el contraste de la imagen especificada. |
|
|  | [setContrast(double value)](#setContrast-double-) | Establece el contraste de la imagen especificada. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


Obtiene una configuración de formato de línea para el borde de la imagen.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


Establece una configuración de formato de línea para el borde de la imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | Instancia de la clase OfficeLineFormat, que representa el formato de línea de forma. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


Obtiene un valor que indica si una imagen se mostrará en modo escala de grises.


**Returns:**
boolean - El valor predeterminado es false.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


Establece un valor que indica si una imagen se mostrará en modo escala de grises.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | El valor predeterminado es false. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


Obtiene el valor de color de la imagen que se tratará como transparente.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


Establece el valor de color de la imagen que se tratará como transparente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | El valor predeterminado es color totalmente transparente. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Obtiene el brillo de la imagen. El valor de esta propiedad debe
ser un número de 0.0 (más tenue) a 1.0 (más brillante).


**Returns:**
double - El valor predeterminado es 0.5.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Establece el brillo de la imagen. El valor de esta propiedad debe
ser un número de 0.0 (más tenue) a 1.0 (más brillante).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | El valor predeterminado es 0.5. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


Obtiene el contraste de la imagen especificada. El valor de esta propiedad
debe ser un número de 0.0 (el contraste más bajo) a 1.0 (el contraste más alto).


**Returns:**
double - El valor predeterminado es 0.5.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


Establece el contraste para la imagen especificada. El valor de esta propiedad
debe ser un número de 0.0 (el contraste más bajo) a 1.0 (el contraste más alto).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | El valor predeterminado es 0.5. |
|

