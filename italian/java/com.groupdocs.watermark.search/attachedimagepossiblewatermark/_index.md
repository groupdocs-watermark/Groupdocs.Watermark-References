---
title: "AttachedImagePossibleWatermark"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una filigrana immagine allegata in un contenuto di qualsiasi formato supportato."
type: docs
weight: 11
url: /it/java/com.groupdocs.watermark.search/attachedimagepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public abstract class AttachedImagePossibleWatermark<T> extends PossibleWatermark
```

Rappresenta una filigrana immagine allegata in un contenuto di qualsiasi formato supportato.


T
: Il tipo dell'allegato.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getParent()](#getParent--) | Restituisce il genitore di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Restituisce la larghezza di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getHeight()](#getHeight--) | Restituisce l'altezza di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getX()](#getX--) | Restituisce la coordinata x di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getY()](#getY--) | Restituisce la coordinata y di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Restituisce l'angolo di rotazione di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` in gradi. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Restituisce l'unità di misura `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getParent() {#getParent--}
```
public ContentPart getParent()
```


Restituisce il genitore di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Restituisce la larghezza di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - La larghezza di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Restituisce l'altezza di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - L'altezza di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Restituisce la coordinata x di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - La coordinata x di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Restituisce la coordinata y di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
double - La coordinata y di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Restituisce l'angolo di rotazione di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Restituisce l'unità di misura `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.


**Returns:**
int - L'unità di misura `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

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




