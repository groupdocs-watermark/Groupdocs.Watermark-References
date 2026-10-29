---
title: "SpreadsheetChart"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un gráfico en un documento de Excel."
type: docs
weight: 106
url: /es/java/com.groupdocs.watermark.contents/spreadsheetchart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer), [com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetChart implements IHyperlinkContainer, ITwoDObject
```

Representa un gráfico en un documento de Excel.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Obtiene la hoja de cálculo principal de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
|
|  | [getId()](#getId--) | Obtiene el identificador de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Obtiene la configuración del formato de relleno de imagen de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
|
|  | [getName()](#getName--) | Obtiene el nombre de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtiene el texto descriptivo (alternativo) asociado a este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
|
|  | [getHyperlink()](#getHyperlink--) | Obtiene el hipervínculo asociado a este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Establece el hipervínculo asociado a este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` desde el borde izquierdo de la hoja de cálculo en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` desde el borde superior de la hoja de cálculo en puntos. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` en puntos. |
|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Obtiene la hoja de cálculo principal de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getId() {#getId--}
```
public final int getId()
```


Obtiene el identificador de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.


**Returns:**
int - El identificador de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Obtiene la configuración del formato de relleno de imagen de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.


**Returns:**
java.lang.String - El nombre de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtiene el texto descriptivo (alternativo) asociado a este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.


**Returns:**
java.lang.String - El texto descriptivo (alternativo) asociado a este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Obtiene el hipervínculo asociado a este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.


**Returns:**
java.lang.String - El hipervínculo asociado a este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Establece el hipervínculo asociado a este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El hipervínculo asociado a este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtiene el desplazamiento horizontal de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` desde el borde izquierdo de la hoja de cálculo en puntos.


**Returns:**
double - La coordenada x de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getY() {#getY--}
```
public final double getY()
```


Obtiene el desplazamiento vertical de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` desde el borde superior de la hoja de cálculo en puntos.


**Returns:**
double - La coordenada y de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene el ancho de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` en puntos.


**Returns:**
double - El ancho de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` en puntos.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene la altura de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` en puntos.


**Returns:**
double - La altura de este `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` en puntos.

