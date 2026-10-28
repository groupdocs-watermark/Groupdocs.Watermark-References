---
title: "AttachedImagePossibleWatermark"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een bijgevoegde afbeeldingswatermark voor in de inhoud van elk ondersteund formaat."
type: docs
weight: 11
url: /nl/java/com.groupdocs.watermark.search/attachedimagepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public abstract class AttachedImagePossibleWatermark<T> extends PossibleWatermark
```

Stelt een bijgevoegde afbeeldingswatermark voor in de inhoud van elk ondersteund formaat.


T
: Het type van de bijlage.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getParent()](#getParent--) | Haalt de ouder op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getX()](#getX--) | Haalt de x-coördinaat op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getY()](#getY--) | Haalt de y-coördinaat op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` in graden. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Haalt de meeteenheid `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` op. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getParent() {#getParent--}
```
public ContentPart getParent()
```


Haalt de ouder op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Haalt de breedte op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - De breedte van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt de hoogte op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - De hoogte van dit `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Haalt de x-coördinaat op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - De x-coördinaat van dit `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Haalt de y-coördinaat op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - De y-coördinaat van dit `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Haalt de rotatiehoek op van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` in graden.


**Returns:**
double - De rotatiehoek van dit `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Haalt de meeteenheid `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` van deze `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` op.


**Returns:**
int - De eenheid van meting `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` van dit `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

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




