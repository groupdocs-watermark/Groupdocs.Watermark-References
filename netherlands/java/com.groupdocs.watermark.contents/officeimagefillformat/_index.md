---
title: "OfficeImageFillFormat"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt de instellingen voor het opvulformaat van afbeeldingen in elke ondersteunde Office-inhoud voor."
type: docs
weight: 46
url: /nl/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Stelt de instellingen voor het opvulformaat van afbeeldingen in elke ondersteunde Office-inhoud voor.


TWatermarkableImage
: Het exacte type van de watermerkbare afbeelding die als achtergrond wordt gebruikt.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Haalt een waarde op die aangeeft of de afbeelding getegeld is over de achtergrond. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Stelt een waarde in die aangeeft of de afbeelding getegeld is over de achtergrond. |
|
|  | [getTransparency()](#getTransparency--) | Haalt de transparantie van de achtergrondafbeelding op als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Stelt de transparantie van de achtergrondafbeelding in als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant). |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Haalt de achtergrondafbeelding op. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Stelt de achtergrondafbeelding in. |
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


Haalt een waarde op die aangeeft of de afbeelding getegeld is over de achtergrond.


**Returns:**
boolean - True als de afbeelding getegeld wordt over de achtergrond; anders false (de afbeelding wordt uitgerekt).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Stelt een waarde in die aangeeft of de afbeelding getegeld is over de achtergrond.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | True als de afbeelding getegeld wordt over de achtergrond; anders false (de afbeelding wordt uitgerekt). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Haalt de transparantie van de achtergrondafbeelding op als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant).


**Returns:**
double - De transparantie van de achtergrondafbeelding als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant).

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Stelt de transparantie van de achtergrondafbeelding in als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De transparantie van de achtergrondafbeelding als een waarde van 0.0 (ondoorzichtig) tot 1.0 (volledig transparant). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Haalt de achtergrondafbeelding op.


**Returns:**
TWatermarkableImage - De achtergrondafbeelding. Retourneert null als de afbeelding niet is ingesteld.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Stelt de achtergrondafbeelding in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | TWatermarkableImage | De achtergrondafbeelding. Retourneert null als de afbeelding niet is ingesteld. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



