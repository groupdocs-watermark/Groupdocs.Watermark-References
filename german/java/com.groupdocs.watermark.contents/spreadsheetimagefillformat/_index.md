---
title: "SpreadsheetImageFillFormat"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt die Bildfüllformat-Einstellungen in einem Excel-Dokument dar."
type: docs
weight: 114
url: /de/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Stellt die Bildfüllformat-Einstellungen in einem Excel-Dokument dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Liefert einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Setzt einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist. |
|
|  | [getTransparency()](#getTransparency--) | Liefert die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) |
bis 1,0 (vollständig transparent).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Setzt die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) |
bis 1,0 (vollständig transparent).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Liefert das Hintergrundbild. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Setzt das Hintergrundbild. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Liefert einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist.


**Returns:**
boolean - Wahr, wenn das Bild über den Hintergrund gekachelt ist; andernfalls falsch (das Bild wird gestreckt).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Setzt einen Wert, der angibt, ob das Bild über den Hintergrund gekachelt ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Wahr, wenn das Bild über den Hintergrund gekachelt ist; andernfalls falsch (das Bild wird gestreckt). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Liefert die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig)
bis 1,0 (vollständig transparent).


**Returns:**
double - Die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 (vollständig transparent).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Setzt die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig)
bis 1,0 (vollständig transparent).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die Transparenz des Hintergrundbildes als Wert von 0,0 (undurchsichtig) bis 1,0 (vollständig transparent). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Liefert das Hintergrundbild.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Setzt das Hintergrundbild.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Das Hintergrundbild. Gibt null zurück, wenn das Bild nicht gesetzt ist. |
|

