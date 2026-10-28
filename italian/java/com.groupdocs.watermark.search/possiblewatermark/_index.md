---
title: "PossibleWatermark"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una possibile filigrana trovata in un documento."
type: docs
weight: 45
url: /it/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

Rappresenta una possibile filigrana trovata in un documento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getParent()](#getParent--) | Ottiene il genitore di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getX()](#getX--) | Ottiene la coordinata x di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getY()](#getY--) | Ottiene la coordinata y di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene l'angolo di rotazione di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` in gradi. |
|
|  | [getText()](#getText--) | Ottiene il testo di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il testo di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Ottiene la raccolta di frammenti di testo formattato di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getImageData()](#getImageData--) | Ottiene o imposta l'immagine di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Ottiene l'unità di misura `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
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


Ottiene il genitore di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


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


Ottiene la larghezza di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La larghezza di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ottiene l'altezza di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - L'altezza di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Ottiene la coordinata x di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La coordinata x di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Ottiene la coordinata y di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La coordinata y di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Ottiene l'angolo di rotazione di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getText() {#getText--}
```
public String getText()
```


Ottiene il testo di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
java.lang.String - Il testo di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Imposta il testo di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Ottiene la raccolta di frammenti di testo formattato di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Ottiene o imposta l'immagine di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
byte[] - L'immagine di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` o null se il watermark non ha immagine.

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Ottiene l'unità di misura `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
int - L'unità di misura `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

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
| Parametro | Tipo | Descrizione |
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




