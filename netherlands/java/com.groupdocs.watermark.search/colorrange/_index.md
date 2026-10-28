---
title: "ColorRange"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een bereik van kleuren voor."
type: docs
weight: 12
url: /nl/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Stelt een bereik van kleuren voor. Specificeert bereiken met behulp van de HSB-representatie van RGB-kleur.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | Initialiseert een nieuw exemplaar van de klasse `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Initialiseert een nieuw exemplaar van de klasse `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` met een opgegeven exacte kleur. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | Haalt de beginkleurtoon op, in graden. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | Stelt de beginkleurtoon in, in graden. |
|
|  | [getMaxHue()](#getMaxHue--) | Haalt de eindkleurtoon op, in graden. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | Stelt de eindkleurtoon in, in graden. |
|
|  | [getMinSaturation()](#getMinSaturation--) | Haalt de beginsaturatiewaarde op. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | Stelt de beginsaturatiewaarde in. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | Haalt de eindsaturatiewaarde op. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | Stelt de eindsaturatiewaarde in. |
|
|  | [getMinBrightness()](#getMinBrightness--) | Haalt de beginkleurhelderheidswaarde op. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | Stelt de beginkleurhelderheidswaarde in. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | Haalt de eindkleurhelderheidswaarde op. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | Stelt de eindkleurhelderheidswaarde in. |
|
|  | [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of alleen de lege kleur binnen het bereik ligt. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | Stelt een waarde in die aangeeft of alleen de lege kleur binnen het bereik ligt. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Initialiseert een nieuw exemplaar van de klasse `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Initialiseert een nieuw exemplaar van de klasse `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` met een opgegeven exacte kleur.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | De exacte kleur waaruit het bereik wordt gemaakt. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Haalt de beginkleurtoon op, in graden.


**Returns:**
float - De beginnende tintwaarde, in graden.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Stelt de beginkleurtoon in, in graden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | De beginnende tintwaarde, in graden. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Haalt de eindkleurtoon op, in graden.


**Returns:**
float - De eindtintwaarde, in graden.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Stelt de eindkleurtoon in, in graden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | De eindtintwaarde, in graden. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Haalt de beginsaturatiewaarde op.


**Returns:**
float - De verzadiging varieert van 0.0 tot 1.0, waarbij 0.0 grijstinten is en 1.0 het meest verzadigd.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Stelt de beginsaturatiewaarde in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | De verzadiging varieert van 0.0 tot 1.0, waarbij 0.0 grijstinten is en 1.0 het meest verzadigd. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Haalt de eindsaturatiewaarde op.


**Returns:**
float - De verzadiging varieert van 0.0 tot 1.0, waarbij 0.0 grijstinten is en 1.0 het meest verzadigd.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Stelt de eindsaturatiewaarde in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | De verzadiging varieert van 0.0 tot 1.0, waarbij 0.0 grijstinten is en 1.0 het meest verzadigd. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Haalt de beginkleurhelderheidswaarde op.


**Returns:**
float - De helderheid varieert van 0.0 tot 1.0, waarbij 0.0 zwart vertegenwoordigt en 1.0 wit vertegenwoordigt.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Stelt de beginkleurhelderheidswaarde in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | De helderheid varieert van 0.0 tot 1.0, waarbij 0.0 zwart vertegenwoordigt en 1.0 wit vertegenwoordigt. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Haalt de eindkleurhelderheidswaarde op.


**Returns:**
float - De helderheid varieert van 0.0 tot 1.0, waarbij 0.0 zwart vertegenwoordigt en 1.0 wit vertegenwoordigt.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Stelt de eindkleurhelderheidswaarde in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | De helderheid varieert van 0.0 tot 1.0, waarbij 0.0 zwart vertegenwoordigt en 1.0 wit vertegenwoordigt. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Haalt een waarde op die aangeeft of alleen de lege kleur binnen het bereik ligt.


**Returns:**
boolean - True als alleen de lege kleur binnen het bereik ligt (HSB-bereiken worden genegeerd); anders false.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Stelt een waarde in die aangeeft of alleen de lege kleur binnen het bereik ligt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | True als alleen de lege kleur binnen het bereik ligt (HSB-bereiken worden genegeerd); anders false. |
|

