---
title: "OfficeImageFillFormat"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa la configuración del formato de relleno de imagen en cualquier contenido de oficina compatible."
type: docs
weight: 46
url: /es/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Representa la configuración del formato de relleno de imagen en cualquier contenido de oficina compatible.


TWatermarkableImage
: El tipo exacto de la imagen marcable que se usa como fondo.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Obtiene un valor que indica si la imagen está en mosaico en el fondo. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Establece un valor que indica si la imagen está en mosaico en el fondo. |
|
|  | [getTransparency()](#getTransparency--) | Obtiene la transparencia de la imagen de fondo como un valor de 0.0 (opaco) a 1.0 (totalmente transparente). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Establece la transparencia de la imagen de fondo como un valor de 0.0 (opaco) a 1.0 (totalmente transparente). |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Obtiene la imagen de fondo. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Establece la imagen de fondo. |
|
|  | [checkIfBackgroundImageIsSet()](#checkIfBackgroundImageIsSet--) | <br /> |

|
### OfficeImageFillFormat() {#OfficeImageFillFormat--}
```
public OfficeImageFillFormat()
```


<br />



### getTileAsTexture() {#getTileAsTexture--}
```
public abstract boolean getTileAsTexture()
```


Obtiene un valor que indica si la imagen está en mosaico en el fondo.


**Returns:**
boolean - Verdadero si la imagen se repite en el fondo; de lo contrario, falso (la imagen se estira).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Establece un valor que indica si la imagen está en mosaico en el fondo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Verdadero si la imagen se repite en el fondo; de lo contrario, falso (la imagen se estira). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Obtiene la transparencia de la imagen de fondo como un valor de 0.0 (opaco) a 1.0 (totalmente transparente).


**Returns:**
double - La transparencia de la imagen de fondo como un valor de 0.0 (opaco) hasta 1.0 (totalmente transparente).

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Establece la transparencia de la imagen de fondo como un valor de 0.0 (opaco) a 1.0 (totalmente transparente).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La transparencia de la imagen de fondo como un valor de 0.0 (opaco) hasta 1.0 (totalmente transparente). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Obtiene la imagen de fondo.


**Returns:**
TWatermarkableImage - La imagen de fondo. Devuelve null si la imagen no está establecida.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Establece la imagen de fondo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | TWatermarkableImage | La imagen de fondo. Devuelve null si la imagen no está establecida. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



