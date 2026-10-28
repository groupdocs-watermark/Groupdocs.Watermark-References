---
title: "SpreadsheetImageFillFormat"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le impostazioni del formato di riempimento immagine in un documento Excel."
type: docs
weight: 114
url: /it/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Rappresenta le impostazioni del formato di riempimento immagine in un documento Excel.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Restituisce un valore che indica se l'immagine è ripetuta sullo sfondo. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Imposta un valore che indica se l'immagine è ripetuta sullo sfondo. |
|
|  | [getTransparency()](#getTransparency--) | Ottiene la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) |
fino a 1.0 (completamente trasparente).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Imposta la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) |
fino a 1.0 (completamente trasparente).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Ottiene l'immagine di sfondo. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Imposta l'immagine di sfondo. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Restituisce un valore che indica se l'immagine è ripetuta sullo sfondo.


**Returns:**
boolean - True se l'immagine è ripetuta sullo sfondo; altrimenti, false (l'immagine è allungata).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Imposta un valore che indica se l'immagine è ripetuta sullo sfondo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | True se l'immagine è ripetuta sullo sfondo; altrimenti, false (l'immagine è allungata). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Ottiene la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco)
fino a 1.0 (completamente trasparente).


**Returns:**
double - La trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) fino a 1.0 (completamente trasparente).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Imposta la trasparenza dell'immagine di sfondo come valore da 0.0 (opaco)
fino a 1.0 (completamente trasparente).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La trasparenza dell'immagine di sfondo come valore da 0.0 (opaco) fino a 1.0 (completamente trasparente). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Ottiene l'immagine di sfondo.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Imposta l'immagine di sfondo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | L'immagine di sfondo. Restituisce null se l'immagine non è impostata. |
|

