---
title: "PossibleWatermark"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una posible marca de agua encontrada en un documento."
type: docs
weight: 45
url: /es/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

Representa una posible marca de agua encontrada en un documento.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getParent()](#getParent--) | Obtiene el padre de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getX()](#getX--) | Obtiene la coordenada x de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getY()](#getY--) | Obtiene la coordenada y de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` en grados. |
|
|  | [getText()](#getText--) | Obtiene el texto de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Establece el texto de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtiene la colección de fragmentos de texto formateado de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getImageData()](#getImageData--) | Obtiene o establece la imagen de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Obtiene la unidad de medida `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [getCollection()](#getCollection--) |  |
| [setCollection(PossibleWatermarkCollection value)](#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-) |  |
| [getImageSize()](#getImageSize--) |  |
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PossibleWatermark() {#PossibleWatermark--}
```
public PossibleWatermark()
```




### getParent() {#getParent--}
```
public abstract ContentPart getParent()
```


Obtiene el padre de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - El ancho de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La altura de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Obtiene la coordenada x de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La coordenada x de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Obtiene la coordenada y de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La coordenada y de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtiene el ángulo de rotación de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` en grados.


**Returns:**
double - El ángulo de rotación de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getText() {#getText--}
```
public String getText()
```


Obtiene el texto de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
java.lang.String - El texto de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Establece el texto de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El texto de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtiene la colección de fragmentos de texto formateado de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Obtiene o establece la imagen de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
byte[] - La imagen de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` o null si la marca de agua no tiene imagen.

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Obtiene la unidad de medida `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
int - La unidad de medida `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getCollection() {#getCollection--}
```
public final PossibleWatermarkCollection getCollection()
```




**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### setCollection(PossibleWatermarkCollection value) {#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void setCollection(PossibleWatermarkCollection value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```




**Returns:**
[Size](../../com.groupdocs.watermark.internal/size)
### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public abstract void remove()
```




