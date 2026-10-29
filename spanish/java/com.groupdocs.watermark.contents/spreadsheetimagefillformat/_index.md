---
title: "SpreadsheetImageFillFormat"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa la configuración del formato de relleno de imagen en un documento de Excel."
type: docs
weight: 114
url: /es/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Representa la configuración del formato de relleno de imagen en un documento de Excel.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Obtiene un valor que indica si la imagen está en mosaico en el fondo. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Establece un valor que indica si la imagen está en mosaico en el fondo. |
|
|  | [getTransparency()](#getTransparency--) | Obtiene la transparencia de la imagen de fondo como un valor de 0.0 (opaco) |
hasta 1.0 (totalmente transparente).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Establece la transparencia de la imagen de fondo como un valor de 0.0 (opaco) |
hasta 1.0 (totalmente transparente).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Obtiene la imagen de fondo. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Establece la imagen de fondo. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Obtiene un valor que indica si la imagen está en mosaico en el fondo.


**Returns:**
boolean - Verdadero si la imagen se repite en el fondo; de lo contrario, falso (la imagen se estira).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Establece un valor que indica si la imagen está en mosaico en el fondo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Verdadero si la imagen se repite en el fondo; de lo contrario, falso (la imagen se estira). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Obtiene la transparencia de la imagen de fondo como un valor de 0.0 (opaco)
hasta 1.0 (totalmente transparente).


**Returns:**
double - La transparencia de la imagen de fondo como un valor de 0.0 (opaco) hasta 1.0 (totalmente transparente).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Establece la transparencia de la imagen de fondo como un valor de 0.0 (opaco)
hasta 1.0 (totalmente transparente).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La transparencia de la imagen de fondo como un valor de 0.0 (opaco) hasta 1.0 (totalmente transparente). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Obtiene la imagen de fondo.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Establece la imagen de fondo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | La imagen de fondo. Devuelve null si la imagen no está establecida. |
|

