---
title: "ColorRange"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar ett färgområde."
type: docs
weight: 12
url: /sv/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Representerar ett färgområde. Anger intervall med HSB-representation av RGB-färg.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | Initierar en ny instans av klassen `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Initierar en ny instans av klassen `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` med en specificerad exakt färg. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | Hämtar starttonvärdet i grader. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | Ställer in starttonvärdet i grader. |
|
|  | [getMaxHue()](#getMaxHue--) | Hämtar sluttonvärdet i grader. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | Ställer in sluttonvärdet i grader. |
|
|  | [getMinSaturation()](#getMinSaturation--) | Hämtar startmättnadsvärdet. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | Ställer in startmättnadsvärdet. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | Hämtar slutmättnadsvärdet. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | Ställer in slutmättnadsvärdet. |
|
|  | [getMinBrightness()](#getMinBrightness--) | Hämtar startvärdet för ljusstyrka. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | Ställer in startvärdet för ljusstyrka. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | Hämtar slutvärdet för ljusstyrka. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | Ställer in slutvärdet för ljusstyrka. |
|
|  | [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om endast den tomma färgen är inom intervallet. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | Ställer in ett värde som indikerar om endast den tomma färgen är inom intervallet. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Initierar en ny instans av klassen `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Initierar en ny instans av klassen `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` med en specificerad exakt färg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Den exakta färgen som intervallet skapas från. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Hämtar starttonvärdet i grader.


**Returns:**
float - Starttonvärdet i grader.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Ställer in starttonvärdet i grader.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | Starttonvärdet i grader. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Hämtar sluttonvärdet i grader.


**Returns:**
float - Sluttonvärdet i grader.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Ställer in sluttonvärdet i grader.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | Sluttonvärdet i grader. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Hämtar startmättnadsvärdet.


**Returns:**
float - Mättnaden varierar från 0.0 till 1.0, där 0.0 är gråskala och 1.0 är mest mättad.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Ställer in startmättnadsvärdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | Mättnaden varierar från 0.0 till 1.0, där 0.0 är gråskala och 1.0 är mest mättad. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Hämtar slutmättnadsvärdet.


**Returns:**
float - Mättnaden varierar från 0.0 till 1.0, där 0.0 är gråskala och 1.0 är mest mättad.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Ställer in slutmättnadsvärdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | Mättnaden varierar från 0.0 till 1.0, där 0.0 är gråskala och 1.0 är mest mättad. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Hämtar startvärdet för ljusstyrka.


**Returns:**
float - Ljusstyrkan varierar från 0.0 till 1.0, där 0.0 representerar svart och 1.0 representerar vitt.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Ställer in startvärdet för ljusstyrka.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | Ljusstyrkan varierar från 0.0 till 1.0, där 0.0 representerar svart och 1.0 representerar vitt. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Hämtar slutvärdet för ljusstyrka.


**Returns:**
float - Ljusstyrkan varierar från 0.0 till 1.0, där 0.0 representerar svart och 1.0 representerar vitt.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Ställer in slutvärdet för ljusstyrka.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | Ljusstyrkan varierar från 0.0 till 1.0, där 0.0 representerar svart och 1.0 representerar vitt. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Hämtar ett värde som indikerar om endast den tomma färgen är inom intervallet.


**Returns:**
boolean - Sant om endast den tomma färgen är inom intervallet (HSB-intervall ignoreras); annars falskt.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Ställer in ett värde som indikerar om endast den tomma färgen är inom intervallet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Sant om endast den tomma färgen är inom intervallet (HSB-intervall ignoreras); annars falskt. |
|

