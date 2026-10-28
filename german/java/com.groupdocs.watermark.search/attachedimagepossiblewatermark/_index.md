---
title: "AttachedImagePossibleWatermark"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein angehängtes Bildwasserzeichen im Inhalt eines beliebigen unterstützten Formats dar."
type: docs
weight: 11
url: /de/java/com.groupdocs.watermark.search/attachedimagepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public abstract class AttachedImagePossibleWatermark<T> extends PossibleWatermark
```

Stellt ein angehängtes Bildwasserzeichen im Inhalt eines beliebigen unterstützten Formats dar.


T
: Der Typ des Anhangs.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getParent()](#getParent--) | Gibt das übergeordnete Element dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück. |
|
|  | [getWidth()](#getWidth--) | Gibt die Breite dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück. |
|
|  | [getHeight()](#getHeight--) | Gibt die Höhe dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück. |
|
|  | [getX()](#getX--) | Gibt die x-Koordinate dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück. |
|
|  | [getY()](#getY--) | Gibt die y-Koordinate dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Gibt den Rotationswinkel dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` in Grad zurück. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Gibt die Maßeinheit `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getParent() {#getParent--}
```
public ContentPart getParent()
```


Gibt das übergeordnete Element dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gibt die Breite dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück.


**Returns:**
double - Die Breite dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gibt die Höhe dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück.


**Returns:**
double - Die Höhe dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Gibt die x-Koordinate dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück.


**Returns:**
double - Die x-Koordinate dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Gibt die y-Koordinate dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück.


**Returns:**
double - Die y-Koordinate dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gibt den Rotationswinkel dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` in Grad zurück.


**Returns:**
double - Der Rotationswinkel dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Gibt die Maßeinheit `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` zurück.


**Returns:**
int - Die Maßeinheit `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dieses `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

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




