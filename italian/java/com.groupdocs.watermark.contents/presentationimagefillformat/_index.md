---
title: "PresentationImageFillFormat"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le impostazioni del formato di riempimento immagine in un documento PowerPoint."
type: docs
weight: 85
url: /it/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

Rappresenta le impostazioni del formato di riempimento immagine in un documento PowerPoint.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Restituisce un valore che indica se l'immagine è ripetuta sullo sfondo. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Imposta un valore che indica se l'immagine è ripetuta sullo sfondo. |
|
|  | [getTransparency()](#getTransparency--) | Restituisce la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) a 1.0 |
(completamente trasparente).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Imposta la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) a 1.0 |
(completamente trasparente).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Ottiene l'immagine di sfondo. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Imposta l'immagine di sfondo. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Restituisce un valore che indica se l'immagine è ripetuta sullo sfondo.


**Returns:**
boolean - True se l'immagine è ripetuta sullo sfondo; altrimenti, false (l'immagine è allungata). Il valore predefinito è false.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Imposta un valore che indica se l'immagine è ripetuta sullo sfondo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | True se l'immagine è ripetuta sullo sfondo; altrimenti, false (l'immagine è allungata). Il valore predefinito è false. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Restituisce la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) a 1.0
(completamente trasparente).


**Returns:**
double - La trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) fino a 1.0 (completamente trasparente).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Imposta la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) a 1.0
(completamente trasparente).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) fino a 1.0 (completamente trasparente). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Ottiene l'immagine di sfondo.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Imposta l'immagine di sfondo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | L'immagine di sfondo. Restituisce null se l'immagine non è impostata. |
|

