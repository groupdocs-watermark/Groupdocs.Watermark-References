---
title: "OfficeImageFillFormat"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar bildfyllningsformatinställningarna i vilket som helst stödjande office‑innehåll."
type: docs
weight: 46
url: /sv/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Representerar bildfyllningsformatinställningarna i vilket som helst stödjande office‑innehåll.


TWatermarkableImage
: Den exakta typen av den vattenstämplade bilden som används som bakgrund.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Hämtar ett värde som indikerar om bilden är kaklad över bakgrunden. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Ställer in ett värde som indikerar om bilden är kaklad över bakgrunden. |
|
|  | [getTransparency()](#getTransparency--) | Hämtar transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Ställer in transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent). |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Hämtar bakgrundsbilden. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Ställer in bakgrundsbilden. |
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


Hämtar ett värde som indikerar om bilden är kaklad över bakgrunden.


**Returns:**
boolean - Sant om bilden är kaklad över bakgrunden; annars falskt (bilden är sträckt).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Ställer in ett värde som indikerar om bilden är kaklad över bakgrunden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Sant om bilden är kaklad över bakgrunden; annars falskt (bilden är sträckt). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Hämtar transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent).


**Returns:**
double - Transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent).

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Ställer in transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Hämtar bakgrundsbilden.


**Returns:**
TWatermarkableImage - Bakgrundsbilden. Returnerar null om bilden inte är angiven.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Ställer in bakgrundsbilden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | TWatermarkableImage | Bakgrundsbilden. Returnerar null om bilden inte är inställd. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



