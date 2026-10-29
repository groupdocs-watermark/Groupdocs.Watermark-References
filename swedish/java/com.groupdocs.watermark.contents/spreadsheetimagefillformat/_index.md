---
title: "SpreadsheetImageFillFormat"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar bildfyllnadsformatinställningarna i ett Excel-dokument."
type: docs
weight: 114
url: /sv/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Representerar bildfyllnadsformatinställningarna i ett Excel-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Hämtar ett värde som indikerar om bilden är kaklad över bakgrunden. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Ställer in ett värde som indikerar om bilden är kaklad över bakgrunden. |
|
|  | [getTransparency()](#getTransparency--) | Hämtar transparensen för bakgrundsbilden som ett värde från 0.0 (opak) |
till 1.0 (fullt transparent).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Ställer in transparensen för bakgrundsbilden som ett värde från 0.0 (opak) |
till 1.0 (fullt transparent).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Hämtar bakgrundsbilden. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Ställer in bakgrundsbilden. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Hämtar ett värde som indikerar om bilden är kaklad över bakgrunden.


**Returns:**
boolean - Sant om bilden är kaklad över bakgrunden; annars falskt (bilden är sträckt).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Ställer in ett värde som indikerar om bilden är kaklad över bakgrunden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Sant om bilden är kaklad över bakgrunden; annars falskt (bilden är sträckt). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Hämtar transparensen för bakgrundsbilden som ett värde från 0.0 (opak)
till 1.0 (fullt transparent).


**Returns:**
double - Transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Ställer in transparensen för bakgrundsbilden som ett värde från 0.0 (opak)
till 1.0 (fullt transparent).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Hämtar bakgrundsbilden.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Ställer in bakgrundsbilden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Bakgrundsbilden. Returnerar null om bilden inte är inställd. |
|

