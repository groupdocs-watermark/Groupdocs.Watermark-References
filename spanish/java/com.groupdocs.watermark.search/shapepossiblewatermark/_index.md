---
title: "ShapePossibleWatermark"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una marca de agua de forma en el contenido de cualquier formato compatible."
type: docs
weight: 55
url: /es/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Representa una marca de agua de forma en el contenido de cualquier formato compatible.


T
: El tipo de la forma.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de la forma en grados. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtiene la colección de fragmentos de texto formateado de la forma. |
|
|  | [getText()](#getText--) | Obtiene el texto de la forma. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Establece el texto de la forma. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtiene el ángulo de rotación de la forma en grados.


**Returns:**
double - El ángulo de rotación de la forma en grados.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtiene la colección de fragmentos de texto formateado de la forma.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


Obtiene el texto de la forma.


**Returns:**
java.lang.String - El texto de la forma.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Establece el texto de la forma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El texto de la forma. |
|

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




