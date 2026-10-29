---
title: "SpreadsheetHeaderFooterPossibleWatermark"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una posible marca de agua en el encabezado o pie de página de un documento de Excel."
type: docs
weight: 62
url: /es/java/com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class SpreadsheetHeaderFooterPossibleWatermark extends PossibleWatermark
```

Representa una posible marca de agua en el encabezado o pie de página de un documento de Excel.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section)](#SpreadsheetHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetHeaderFooterSection-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getParent()](#getParent--) | Obtiene el padre de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en puntos. |
|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` desde el borde izquierdo de la hoja de cálculo en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` desde el borde superior de la hoja de cálculo en puntos. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en grados. |
|
|  | [getText()](#getText--) | Obtiene el texto de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Establece el texto de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Obtiene la `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section) {#SpreadsheetHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetHeaderFooterSection-}
```
public SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Obtiene el padre de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en puntos.


**Returns:**
double - El ancho de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en puntos.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en puntos.


**Returns:**
double - La altura de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en puntos.

### getX() {#getX--}
```
public double getX()
```


Obtiene el desplazamiento horizontal de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` desde el borde izquierdo de la hoja de cálculo en puntos.


**Returns:**
double - La coordenada x de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Obtiene el desplazamiento vertical de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` desde el borde superior de la hoja de cálculo en puntos.


**Returns:**
double - La coordenada y de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtiene el ángulo de rotación de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en grados.


**Returns:**
double - El ángulo de rotación de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en grados.

### getText() {#getText--}
```
public String getText()
```


Obtiene el texto de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Returns:**
java.lang.String - El texto de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Establece el texto de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El texto de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Obtiene la `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Returns:**
int - La `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




