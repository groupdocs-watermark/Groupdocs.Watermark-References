---
title: "OfficeImageFillFormat"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le impostazioni del formato di riempimento immagine in qualsiasi contenuto Office supportato."
type: docs
weight: 46
url: /it/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Rappresenta le impostazioni del formato di riempimento immagine in qualsiasi contenuto Office supportato.


TWatermarkableImage
: Il tipo esatto dell'immagine watermarkable utilizzata come sfondo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Restituisce un valore che indica se l'immagine è ripetuta sullo sfondo. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Imposta un valore che indica se l'immagine è ripetuta sullo sfondo. |
|
|  | [getTransparency()](#getTransparency--) | Ottiene la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) a 1.0 (completamente trasparente). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Imposta la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) a 1.0 (completamente trasparente). |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Ottiene l'immagine di sfondo. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Imposta l'immagine di sfondo. |
|
|  | [checkIfBackgroundImageIsSet()](#checkIfBackgroundImageIsSet--) | <br /> |

|
### OfficeImageFillFormat() {#OfficeImageFillFormat--}
```
public OfficeImageFillFormat()
```


<br />



### getTileAsTexture() {#getTileAsTexture--}
```
public abstract boolean getTileAsTexture()
```


Restituisce un valore che indica se l'immagine è ripetuta sullo sfondo.


**Returns:**
boolean - True se l'immagine è ripetuta sullo sfondo; altrimenti, false (l'immagine è allungata).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Imposta un valore che indica se l'immagine è ripetuta sullo sfondo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | True se l'immagine è ripetuta sullo sfondo; altrimenti, false (l'immagine è allungata). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Ottiene la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) a 1.0 (completamente trasparente).


**Returns:**
double - La trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) fino a 1.0 (completamente trasparente).

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Imposta la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) a 1.0 (completamente trasparente).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) fino a 1.0 (completamente trasparente). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Ottiene l'immagine di sfondo.


**Returns:**
TWatermarkableImage - L'immagine di sfondo. Restituisce null se l'immagine non è impostata.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Imposta l'immagine di sfondo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | TWatermarkableImage | L'immagine di sfondo. Restituisce null se l'immagine non è impostata. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



