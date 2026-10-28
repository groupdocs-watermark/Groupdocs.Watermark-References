---
title: "PresentationBackgroundPossibleWatermark"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una possibile filigrana di sfondo in un documento PowerPoint."
type: docs
weight: 47
url: /it/java/com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PresentationBackgroundPossibleWatermark extends PossibleWatermark
```

Rappresenta una possibile filigrana di sfondo in un documento PowerPoint.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide)](#PresentationBackgroundPossibleWatermark-com.groupdocs.watermark.contents.PresentationBaseSlide-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getParent()](#getParent--) | Ottiene il genitore di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` in punti. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` in punti. |
|
|  | [getX()](#getX--) | Ottiene lo spostamento orizzontale di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` dal bordo sinistro della diapositiva in punti. |
|
|  | [getY()](#getY--) | Ottiene lo spostamento verticale di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` dal bordo superiore della diapositiva in punti. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene l'angolo di rotazione di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` in gradi. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Ottiene il `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide) {#PresentationBackgroundPossibleWatermark-com.groupdocs.watermark.contents.PresentationBaseSlide-}
```
public PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Ottiene il genitore di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Ottiene la larghezza di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` in punti.


**Returns:**
double - La larghezza di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` in punti.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ottiene l'altezza di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` in punti.


**Returns:**
double - L'altezza di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` in punti.

### getX() {#getX--}
```
public double getX()
```


Ottiene lo spostamento orizzontale di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` dal bordo sinistro della diapositiva in punti.


**Returns:**
double - La coordinata x di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Ottiene lo spostamento verticale di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` dal bordo superiore della diapositiva in punti.


**Returns:**
double - La coordinata y di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Ottiene l'angolo di rotazione di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` in gradi.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Ottiene il `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.


**Returns:**
int - Il `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` di questo `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

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




