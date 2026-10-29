---
title: "SpreadsheetAttachment"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un archivo adjunto a un documento de Excel."
type: docs
weight: 101
url: /es/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Representa un archivo adjunto a un documento de Excel.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getContent()](#getContent--) | Obtiene el contenido del archivo adjunto. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Establece el contenido del archivo adjunto. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | Obtiene la imagen de vista previa del archivo adjunto como una matriz de bytes. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Establece la imagen de vista previa del archivo adjunto como una matriz de bytes. |
|
|  | [isLink()](#isLink--) | Obtiene un valor que indica si el contenido contiene solo un enlace al archivo. |
|
|  | [getSourceFullName()](#getSourceFullName--) | Obtiene el nombre completo del archivo adjunto. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtiene el texto descriptivo (alternativo) asociado al archivo adjunto. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Establece el texto descriptivo (alternativo) asociado al archivo adjunto. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal del marco del adjunto desde el borde izquierdo de la hoja de cálculo en puntos. |
|
|  | [setX(double value)](#setX-double-) | Establece el desplazamiento horizontal del marco del adjunto desde el borde izquierdo de la hoja de cálculo en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical del marco del adjunto desde el borde superior de la hoja de cálculo en puntos. |
|
|  | [setY(double value)](#setY-double-) | Establece el desplazamiento vertical del marco del adjunto desde el borde superior de la hoja de cálculo en puntos. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho del marco del adjunto en puntos. |
|
|  | [setWidth(double value)](#setWidth-double-) | Establece el ancho del marco del adjunto en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura del marco del adjunto en puntos. |
|
|  | [setHeight(double value)](#setHeight-double-) | Establece la altura del marco del adjunto en puntos. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


Obtiene el contenido del archivo adjunto.


**Returns:**
byte[] - El contenido del archivo adjunto.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Establece el contenido del archivo adjunto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte[] | El contenido del archivo adjunto. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Obtiene la imagen de vista previa del archivo adjunto como una matriz de bytes.


**Returns:**
byte[] - La imagen de vista previa del archivo adjunto como una matriz de bytes.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Establece la imagen de vista previa del archivo adjunto como una matriz de bytes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte[] | La imagen de vista previa del archivo adjunto como una matriz de bytes. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


Obtiene un valor que indica si el contenido contiene solo un enlace al archivo.


**Returns:**
boolean - Verdadero si el archivo adjunto está referenciado por un enlace (el contenido no contiene el contenido del archivo adjunto); de lo contrario, falso.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Obtiene el nombre completo del archivo adjunto.


**Returns:**
java.lang.String - El nombre completo del archivo adjunto.

<br />

*** ** * ** ***

La extensión se usa para determinar la aplicación adecuada para abrir el archivo.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtiene el texto descriptivo (alternativo) asociado al archivo adjunto.


**Returns:**
java.lang.String - El texto descriptivo (alternativo) asociado al archivo adjunto.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Establece el texto descriptivo (alternativo) asociado al archivo adjunto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El texto descriptivo (alternativo) asociado al archivo adjunto. |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


Obtiene el desplazamiento horizontal del marco del adjunto desde el borde izquierdo de la hoja de cálculo en puntos.


**Returns:**
double - La coordenada x del marco del adjunto.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Establece el desplazamiento horizontal del marco del adjunto desde el borde izquierdo de la hoja de cálculo en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La coordenada x del marco del adjunto. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtiene el desplazamiento vertical del marco del adjunto desde el borde superior de la hoja de cálculo en puntos.


**Returns:**
double - La coordenada y del marco del adjunto.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Establece el desplazamiento vertical del marco del adjunto desde el borde superior de la hoja de cálculo en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La coordenada y del marco de adjunto. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene el ancho del marco del adjunto en puntos.


**Returns:**
double - El ancho del marco de adjunto en puntos.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Establece el ancho del marco del adjunto en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | El ancho del marco de adjunto en puntos. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene la altura del marco del adjunto en puntos.


**Returns:**
double - La altura del marco de adjunto en puntos.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Establece la altura del marco del adjunto en puntos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La altura del marco de adjunto en puntos. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



