---
title: "SpreadsheetImageFillFormat"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt de instellingen voor afbeeldingsvulling in een Excel‑document voor."
type: docs
weight: 114
url: /nl/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Stelt de instellingen voor afbeeldingsvulling in een Excel‑document voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Haalt een waarde op die aangeeft of de afbeelding getegeld is over de achtergrond. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Stelt een waarde in die aangeeft of de afbeelding getegeld is over de achtergrond. |
|
|  | [getTransparency()](#getTransparency--) | Haalt de transparantie van de achtergrondafbeelding op als een waarde van 0.0 (ondoorzichtig) |
tot 1.0 (volledig transparant).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Stelt de transparantie van de achtergrondafbeelding in als een waarde van 0.0 (ondoorzichtig) |
tot 1.0 (volledig transparant).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Haalt de achtergrondafbeelding op. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Stelt de achtergrondafbeelding in. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Haalt een waarde op die aangeeft of de afbeelding getegeld is over de achtergrond.


**Returns:**
boolean - True als de afbeelding getegeld wordt over de achtergrond; anders false (de afbeelding wordt uitgerekt).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Stelt een waarde in die aangeeft of de afbeelding getegeld is over de achtergrond.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | True als de afbeelding getegeld wordt over de achtergrond; anders false (de afbeelding wordt uitgerekt). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Haalt de transparantie van de achtergrondafbeelding op als een waarde van 0.0 (ondoorzichtig)
tot 1.0 (volledig transparant).


**Returns:**
double - De transparantie van de achtergrondafbeelding als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Stelt de transparantie van de achtergrondafbeelding in als een waarde van 0.0 (ondoorzichtig)
tot 1.0 (volledig transparant).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De transparantie van de achtergrondafbeelding als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Haalt de achtergrondafbeelding op.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Stelt de achtergrondafbeelding in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | De achtergrondafbeelding. Retourneert null als de afbeelding niet is ingesteld. |
|

