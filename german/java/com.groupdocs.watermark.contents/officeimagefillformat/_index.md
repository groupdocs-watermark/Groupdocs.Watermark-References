---
title: "OfficeImageFillFormat"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt die Einstellungen für das Bildfüllformat in beliebigen unterstützten Office-Inhalten dar."
type: docs
weight: 46
url: /de/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Stellt die Einstellungen für das Bildfüllformat in beliebigen unterstützten Office-Inhalten dar.


TWatermarkableImage
: Der genaue Typ des watermarkable image, das als Hintergrund verwendet wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Liefert einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Setzt einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist. |
|
|  | [getTransparency()](#getTransparency--) | Ermittelt die Transparenz des Hintergrundbildes als Wert von 0.0 (undurchsichtig) bis 1.0 (vollständig transparent). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Legt die Transparenz des Hintergrundbildes als Wert von 0.0 (undurchsichtig) bis 1.0 (vollständig transparent) fest. |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Liefert das Hintergrundbild. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Setzt das Hintergrundbild. |
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


Liefert einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist.


**Returns:**
boolean - Wahr, wenn das Bild über den Hintergrund gekachelt ist; andernfalls falsch (das Bild wird gestreckt).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Setzt einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Wahr, wenn das Bild über den Hintergrund gekachelt ist; andernfalls falsch (das Bild wird gestreckt). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Ermittelt die Transparenz des Hintergrundbildes als Wert von 0.0 (undurchsichtig) bis 1.0 (vollständig transparent).


**Returns:**
double - Die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 (vollständig transparent).

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Legt die Transparenz des Hintergrundbildes als Wert von 0.0 (undurchsichtig) bis 1.0 (vollständig transparent) fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 (vollständig transparent). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Liefert das Hintergrundbild.


**Returns:**
TWatermarkableImage - Das Hintergrundbild. Gibt null zurück, wenn das Bild nicht gesetzt ist.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Setzt das Hintergrundbild.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | TWatermarkableImage | Das Hintergrundbild. Gibt null zurück, wenn das Bild nicht gesetzt ist. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



