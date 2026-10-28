---
title: "ColorRange"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt einen Farbbereich dar."
type: docs
weight: 12
url: /de/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Stellt einen Farbbereich dar. Gibt Bereiche mit der HSB-Darstellung der RGB-Farbe an.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | Initialisiert eine neue Instanz der `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` Klasse. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Initialisiert eine neue Instanz der `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` Klasse mit einer angegebenen exakten Farbe. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | Gibt den Startwert des Farbtons in Grad zurück. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | Setzt den Startwert des Farbtons in Grad. |
|
|  | [getMaxHue()](#getMaxHue--) | Gibt den Endwert des Farbtons in Grad zurück. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | Setzt den Endwert des Farbtons in Grad. |
|
|  | [getMinSaturation()](#getMinSaturation--) | Gibt den Startwert der Sättigung zurück. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | Setzt den Startwert der Sättigung. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | Gibt den Endwert der Sättigung zurück. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | Setzt den Endwert der Sättigung. |
|
|  | [getMinBrightness()](#getMinBrightness--) | Gibt den Startwert der Helligkeit zurück. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | Setzt den Startwert der Helligkeit. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | Gibt den Endwert der Helligkeit zurück. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | Setzt den Endwert der Helligkeit. |
|
|  | [isEmpty()](#isEmpty--) | Gibt einen Wert zurück, der angibt, ob nur die leere Farbe im Bereich liegt. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | Setzt einen Wert, der angibt, ob nur die leere Farbe im Bereich liegt. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Initialisiert eine neue Instanz der `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` Klasse.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Initialisiert eine neue Instanz der `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` Klasse mit einer angegebenen exakten Farbe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Die exakte Farbe, aus der der Bereich erstellt wird. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Gibt den Startwert des Farbtons in Grad zurück.


**Returns:**
float - Der Startwert des Farbtons, in Grad.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Setzt den Startwert des Farbtons in Grad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | Der Startwert des Farbtons, in Grad. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Gibt den Endwert des Farbtons in Grad zurück.


**Returns:**
float - Der Endfarbtonwert, in Grad.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Setzt den Endwert des Farbtons in Grad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | Der Endfarbtonwert, in Grad. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Gibt den Startwert der Sättigung zurück.


**Returns:**
float - Die Sättigung reicht von 0.0 bis 1.0, wobei 0.0 Graustufen und 1.0 am stärksten gesättigt ist.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Setzt den Startwert der Sättigung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | Die Sättigung reicht von 0.0 bis 1.0, wobei 0.0 Graustufen und 1.0 am stärksten gesättigt ist. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Gibt den Endwert der Sättigung zurück.


**Returns:**
float - Die Sättigung reicht von 0.0 bis 1.0, wobei 0.0 Graustufen und 1.0 am stärksten gesättigt ist.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Setzt den Endwert der Sättigung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | Die Sättigung reicht von 0.0 bis 1.0, wobei 0.0 Graustufen und 1.0 am stärksten gesättigt ist. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Gibt den Startwert der Helligkeit zurück.


**Returns:**
float - Die Helligkeit reicht von 0.0 bis 1.0, wobei 0.0 Schwarz und 1.0 Weiß darstellt.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Setzt den Startwert der Helligkeit.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | Die Helligkeit reicht von 0.0 bis 1.0, wobei 0.0 Schwarz und 1.0 Weiß darstellt. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Gibt den Endwert der Helligkeit zurück.


**Returns:**
float - Die Helligkeit reicht von 0.0 bis 1.0, wobei 0.0 Schwarz und 1.0 Weiß darstellt.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Setzt den Endwert der Helligkeit.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | Die Helligkeit reicht von 0.0 bis 1.0, wobei 0.0 Schwarz und 1.0 Weiß darstellt. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Gibt einen Wert zurück, der angibt, ob nur die leere Farbe im Bereich liegt.


**Returns:**
boolean - Wahr, wenn nur die leere Farbe im Bereich liegt (HSB‑Bereiche werden ignoriert); andernfalls falsch.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Setzt einen Wert, der angibt, ob nur die leere Farbe im Bereich liegt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Wahr, wenn nur die leere Farbe im Bereich liegt (HSB‑Bereiche werden ignoriert); andernfalls falsch. |
|

