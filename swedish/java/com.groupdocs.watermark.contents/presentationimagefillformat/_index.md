---
title: "PresentationImageFillFormat"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar bildfyllnadsformatinställningarna i ett PowerPoint-dokument."
type: docs
weight: 85
url: /sv/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

Representerar bildfyllnadsformatinställningarna i ett PowerPoint-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Hämtar ett värde som indikerar om bilden är kaklad över bakgrunden. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Ställer in ett värde som indikerar om bilden är kaklad över bakgrunden. |
|
|  | [getTransparency()](#getTransparency--) | Hämtar transparensen för bakgrundsbilden som ett värde från 0,0 (opak) till 1,0 |
(helt transparent).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Ställer in transparensen för bakgrundsbilden som ett värde från 0,0 (opak) till 1,0 |
(helt transparent).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Hämtar bakgrundsbilden. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Ställer in bakgrundsbilden. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Hämtar ett värde som indikerar om bilden är kaklad över bakgrunden.


**Returns:**
boolean - Sant om bilden är upprepad över bakgrunden; annars falskt (bilden är sträckt). Standardvärdet är falskt.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Ställer in ett värde som indikerar om bilden är kaklad över bakgrunden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Sant om bilden är upprepad över bakgrunden; annars falskt (bilden är sträckt). Standardvärdet är falskt. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Hämtar transparensen för bakgrundsbilden som ett värde från 0,0 (opak) till 1,0
(helt transparent).


**Returns:**
double - Transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Ställer in transparensen för bakgrundsbilden som ett värde från 0,0 (opak) till 1,0
(helt transparent).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Transparensen för bakgrundsbilden som ett värde från 0.0 (opak) till 1.0 (fullt transparent). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Hämtar bakgrundsbilden.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Ställer in bakgrundsbilden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Bakgrundsbilden. Returnerar null om bilden inte är inställd. |
|

