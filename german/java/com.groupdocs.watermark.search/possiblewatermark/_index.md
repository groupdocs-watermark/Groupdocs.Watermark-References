---
title: "PossibleWatermark"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt mögliche Wasserzeichen dar, die in einem Dokument gefunden wurden."
type: docs
weight: 45
url: /de/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

Stellt mögliche Wasserzeichen dar, die in einem Dokument gefunden wurden.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getParent()](#getParent--) | Gibt das übergeordnete Element dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück. |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | Gibt die Breite dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück. |
|
|  | [getHeight()](#getHeight--) | Gibt die Höhe dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück. |
|
|  | [getX()](#getX--) | Gibt die x‑Koordinate dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück. |
|
|  | [getY()](#getY--) | Gibt die y‑Koordinate dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Gibt den Rotationswinkel dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` in Grad zurück. |
|
|  | [getText()](#getText--) | Gibt den Text dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Setzt den Text dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Gibt die Sammlung formatierter Textfragmente dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück. |
|
|  | [getImageData()](#getImageData--) | Liest oder setzt das Bild dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Gibt die Maßeinheit `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück. |
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


Gibt das übergeordnete Element dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück.


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


Gibt die Breite dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück.


**Returns:**
double - Die Breite dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gibt die Höhe dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück.


**Returns:**
double - Die Höhe dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Gibt die x‑Koordinate dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück.


**Returns:**
double - Die x‑Koordinate dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Gibt die y‑Koordinate dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück.


**Returns:**
double - Die y‑Koordinate dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gibt den Rotationswinkel dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` in Grad zurück.


**Returns:**
double - Der Rotationswinkel dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getText() {#getText--}
```
public String getText()
```


Gibt den Text dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück.


**Returns:**
java.lang.String - Der Text dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Setzt den Text dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Text dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Gibt die Sammlung formatierter Textfragmente dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Liest oder setzt das Bild dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
byte[] - Das Bild dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` oder null, wenn das Wasserzeichen kein Bild hat.

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Gibt die Maßeinheit `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` zurück.


**Returns:**
int - Die Maßeinheit `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dieses `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

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
| Parameter | Typ | Beschreibung |
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




