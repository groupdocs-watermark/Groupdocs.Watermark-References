---
title: "PossibleWatermark"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar möjlig vattenstämpel som hittas i ett dokument."
type: docs
weight: 45
url: /sv/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

Representerar möjlig vattenstämpel som hittas i ett dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getParent()](#getParent--) | Hämtar föräldern till detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getX()](#getX--) | Hämtar x‑koordinaten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getY()](#getY--) | Hämtar y‑koordinaten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` i grader. |
|
|  | [getText()](#getText--) | Hämtar texten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Sätter texten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Hämtar samlingen av formaterade textfragment för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getImageData()](#getImageData--) | Hämtar eller sätter bilden för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Hämtar enheten för mätning `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
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


Hämtar föräldern till detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


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


Hämtar bredden på detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - Bredden på detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Hämtar höjden på detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - Höjden på detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Hämtar x‑koordinaten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - x-koordinaten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Hämtar y‑koordinaten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - y-koordinaten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Hämtar rotationsvinkeln för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` i grader.


**Returns:**
double - rotationsvinkeln för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getText() {#getText--}
```
public String getText()
```


Hämtar texten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
java.lang.String - texten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sätter texten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Texten för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Hämtar samlingen av formaterade textfragment för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Hämtar eller sätter bilden för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
byte[] - bilden för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` eller null om vattenstämpeln saknar bild.

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Hämtar enheten för mätning `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
int - måttenheten `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` för detta `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

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
| Parameter | Typ | Beskrivning |
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




