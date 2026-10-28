---
title: "PossibleWatermark"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt mogelijk watermerk gevonden in een document voor."
type: docs
weight: 45
url: /nl/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

Stelt mogelijk watermerk gevonden in een document voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getParent()](#getParent--) | Haalt de ouder van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op. |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | Haalt de breedte van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op. |
|
|  | [getX()](#getX--) | Haalt de x-coördinaat van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op. |
|
|  | [getY()](#getY--) | Haalt de y-coördinaat van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op in graden. |
|
|  | [getText()](#getText--) | Haalt de tekst van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de tekst van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` in. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Haalt de collectie van opgemaakte tekstfragmenten van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op. |
|
|  | [getImageData()](#getImageData--) | Haalt de afbeelding van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op of stelt deze in. |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Haalt de meeteenheid `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op. |
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


Haalt de ouder van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op.


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


Haalt de breedte van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op.


**Returns:**
double - De breedte van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt de hoogte van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op.


**Returns:**
double - De hoogte van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Haalt de x-coördinaat van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op.


**Returns:**
double - De x-coördinaat van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Haalt de y-coördinaat van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op.


**Returns:**
double - De y-coördinaat van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Haalt de rotatiehoek van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op in graden.


**Returns:**
double - De rotatiehoek van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getText() {#getText--}
```
public String getText()
```


Haalt de tekst van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op.


**Returns:**
java.lang.String - De tekst van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Stelt de tekst van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De tekst van deze `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Haalt de collectie van opgemaakte tekstfragmenten van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Haalt de afbeelding van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op of stelt deze in.


**Returns:**
byte[] - De afbeelding van deze `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` of null als het watermerk geen afbeelding heeft.

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Haalt de meeteenheid `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` op.


**Returns:**
int - De meeteenheid `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` van dit `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

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
| Parameter | Type | Beschrijving |
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




