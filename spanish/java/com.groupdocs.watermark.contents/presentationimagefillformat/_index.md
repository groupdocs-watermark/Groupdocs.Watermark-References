---
title: "PresentationImageFillFormat"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa la configuración del formato de relleno de imagen en un documento PowerPoint."
type: docs
weight: 85
url: /es/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

Representa la configuración del formato de relleno de imagen en un documento PowerPoint.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Obtiene un valor que indica si la imagen está en mosaico en el fondo. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Establece un valor que indica si la imagen está en mosaico en el fondo. |
|
|  | [getTransparency()](#getTransparency--) | Obtiene la transparencia de la imagen de fondo como un valor desde 0.0 (opaco) hasta 1.0 |
(totalmente transparente).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Establece la transparencia de la imagen de fondo como un valor desde 0.0 (opaco) hasta 1.0 |
(totalmente transparente).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Obtiene la imagen de fondo. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Establece la imagen de fondo. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Obtiene un valor que indica si la imagen está en mosaico en el fondo.


**Returns:**
boolean - True si la imagen está en mosaico en el fondo; de lo contrario, false (la imagen está estirada). El valor predeterminado es false.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Establece un valor que indica si la imagen está en mosaico en el fondo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | True si la imagen está en mosaico en el fondo; de lo contrario, false (la imagen está estirada). El valor predeterminado es false. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Obtiene la transparencia de la imagen de fondo como un valor desde 0.0 (opaco) hasta 1.0
(totalmente transparente).


**Returns:**
double - La transparencia de la imagen de fondo como un valor de 0.0 (opaco) hasta 1.0 (totalmente transparente).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Establece la transparencia de la imagen de fondo como un valor desde 0.0 (opaco) hasta 1.0
(totalmente transparente).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La transparencia de la imagen de fondo como un valor de 0.0 (opaco) hasta 1.0 (totalmente transparente). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Obtiene la imagen de fondo.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Establece la imagen de fondo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | La imagen de fondo. Devuelve null si la imagen no está establecida. |
|

