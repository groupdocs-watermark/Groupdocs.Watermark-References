---
title: "PresentationImageFillFormat"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt de instellingen voor afbeeldingsvulling in een PowerPoint-document voor."
type: docs
weight: 85
url: /nl/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

Stelt de instellingen voor afbeeldingsvulling in een PowerPoint-document voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Haalt een waarde op die aangeeft of de afbeelding getegeld is over de achtergrond. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Stelt een waarde in die aangeeft of de afbeelding getegeld is over de achtergrond. |
|
|  | [getTransparency()](#getTransparency--) | Haalt de transparantie van de achtergrondafbeelding op als een waarde van 0.0 (ondoorzichtig) tot 1.0 |
(volledig transparant).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Stelt de transparantie van de achtergrondafbeelding in als een waarde van 0.0 (ondoorzichtig) tot 1.0 |
(volledig transparant).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Haalt de achtergrondafbeelding op. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Stelt de achtergrondafbeelding in. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Haalt een waarde op die aangeeft of de afbeelding getegeld is over de achtergrond.


**Returns:**
boolean - True als de afbeelding getegeld is over de achtergrond; anders false (de afbeelding wordt uitgerekt). De standaardwaarde is false.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Stelt een waarde in die aangeeft of de afbeelding getegeld is over de achtergrond.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | True als de afbeelding getegeld is over de achtergrond; anders false (de afbeelding wordt uitgerekt). De standaardwaarde is false. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Haalt de transparantie van de achtergrondafbeelding op als een waarde van 0.0 (ondoorzichtig) tot 1.0
(volledig transparant).


**Returns:**
double - De transparantie van de achtergrondafbeelding als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Stelt de transparantie van de achtergrondafbeelding in als een waarde van 0.0 (ondoorzichtig) tot 1.0
(volledig transparant).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De transparantie van de achtergrondafbeelding als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Haalt de achtergrondafbeelding op.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Stelt de achtergrondafbeelding in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | De achtergrondafbeelding. Retourneert null als de afbeelding niet is ingesteld. |
|

