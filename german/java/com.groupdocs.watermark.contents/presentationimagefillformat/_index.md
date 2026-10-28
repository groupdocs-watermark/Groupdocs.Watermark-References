---
title: "PresentationImageFillFormat"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt die Bildfüllformat-Einstellungen in einem PowerPoint-Dokument dar."
type: docs
weight: 85
url: /de/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

Stellt die Bildfüllformat-Einstellungen in einem PowerPoint-Dokument dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Liefert einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Setzt einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist. |
|
|  | [getTransparency()](#getTransparency--) | Ermittelt die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 |
(vollständig transparent).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Legt die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 fest |
(vollständig transparent).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Liefert das Hintergrundbild. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Setzt das Hintergrundbild. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Liefert einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist.


**Returns:**
boolean – True, wenn das Bild über den Hintergrund gekachelt wird; andernfalls false (das Bild wird gestreckt). Der Standardwert ist false.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Setzt einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | True, wenn das Bild über den Hintergrund gekachelt wird; andernfalls false (das Bild wird gestreckt). Der Standardwert ist false. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Ermittelt die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0
(vollständig transparent).


**Returns:**
double - Die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 (vollständig transparent).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Legt die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 fest
(vollständig transparent).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 (vollständig transparent). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Liefert das Hintergrundbild.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Setzt das Hintergrundbild.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Das Hintergrundbild. Gibt null zurück, wenn das Bild nicht gesetzt ist. |
|

