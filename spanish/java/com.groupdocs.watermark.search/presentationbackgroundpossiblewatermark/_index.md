---
title: "PresentationBackgroundPossibleWatermark"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una posible marca de agua de fondo en un documento PowerPoint."
type: docs
weight: 47
url: /es/java/com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PresentationBackgroundPossibleWatermark extends PossibleWatermark
```

Representa una posible marca de agua de fondo en un documento PowerPoint.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide)](#PresentationBackgroundPossibleWatermark-com.groupdocs.watermark.contents.PresentationBaseSlide-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getParent()](#getParent--) | Obtiene el padre de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` en puntos. |
|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` desde el borde izquierdo de la diapositiva en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` desde el borde superior de la diapositiva en puntos. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` en grados. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Obtiene la `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide) {#PresentationBackgroundPossibleWatermark-com.groupdocs.watermark.contents.PresentationBaseSlide-}
```
public PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Obtiene el padre de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` en puntos.


**Returns:**
double - El ancho de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` en puntos.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` en puntos.


**Returns:**
double - La altura de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` en puntos.

### getX() {#getX--}
```
public double getX()
```


Obtiene el desplazamiento horizontal de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` desde el borde izquierdo de la diapositiva en puntos.


**Returns:**
double - La coordenada x de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Obtiene el desplazamiento vertical de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` desde el borde superior de la diapositiva en puntos.


**Returns:**
double - La coordenada y de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtiene el ángulo de rotación de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` en grados.


**Returns:**
double - El ángulo de rotación de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` en grados.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Obtiene la `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.


**Returns:**
int - La `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

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




