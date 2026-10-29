---
title: "AttachedImagePossibleWatermark"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar bifogad bildvattenstämpel i ett innehåll av något stödt format."
type: docs
weight: 11
url: /sv/java/com.groupdocs.watermark.search/attachedimagepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public abstract class AttachedImagePossibleWatermark<T> extends PossibleWatermark
```

Representerar bifogad bildvattenstämpel i ett innehåll av något stödt format.


T
: Typen av bilagan.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getParent()](#getParent--) | Hämtar föräldern till detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getX()](#getX--) | Hämtar x-koordinaten för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getY()](#getY--) | Hämtar y-koordinaten för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` i grader. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Hämtar enheten `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getParent() {#getParent--}
```
public ContentPart getParent()
```


Hämtar föräldern till detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Hämtar bredden på detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - Bredden på detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Hämtar höjden på detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - Höjden på detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Hämtar x-koordinaten för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - x-koordinaten för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Hämtar y-koordinaten för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - y-koordinaten för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Hämtar rotationsvinkeln för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` i grader.


**Returns:**
double - rotationsvinkeln för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Hämtar enheten `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
int - Enheten `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` för detta `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

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




