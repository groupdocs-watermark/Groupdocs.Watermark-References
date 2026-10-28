---
title: "ColorRange"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una gamma di colori."
type: docs
weight: 12
url: /it/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Rappresenta un intervallo di colori. Specifica gli intervalli usando la rappresentazione HSB del colore RGB.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | Inizializza una nuova istanza della classe `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Inizializza una nuova istanza della classe `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` con un colore esatto specificato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | Ottiene il valore di tonalità iniziale, in gradi. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | Imposta il valore di tonalità iniziale, in gradi. |
|
|  | [getMaxHue()](#getMaxHue--) | Ottiene il valore di tonalità finale, in gradi. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | Imposta il valore di tonalità finale, in gradi. |
|
|  | [getMinSaturation()](#getMinSaturation--) | Ottiene il valore di saturazione iniziale. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | Imposta il valore di saturazione iniziale. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | Ottiene il valore di saturazione finale. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | Imposta il valore di saturazione finale. |
|
|  | [getMinBrightness()](#getMinBrightness--) | Ottiene il valore di luminosità iniziale. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | Imposta il valore di luminosità iniziale. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | Ottiene il valore di luminosità finale. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | Imposta il valore di luminosità finale. |
|
|  | [isEmpty()](#isEmpty--) | Ottiene un valore che indica se solo il colore vuoto è nell'intervallo. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | Imposta un valore che indica se solo il colore vuoto è nell'intervallo. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Inizializza una nuova istanza della classe `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Inizializza una nuova istanza della classe `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` con un colore esatto specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore esatto da cui viene creato l'intervallo. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Ottiene il valore di tonalità iniziale, in gradi.


**Returns:**
float - Il valore iniziale della tonalità, in gradi.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Imposta il valore di tonalità iniziale, in gradi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | Il valore iniziale della tonalità, in gradi. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Ottiene il valore di tonalità finale, in gradi.


**Returns:**
float - Il valore finale della tonalità, in gradi.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Imposta il valore di tonalità finale, in gradi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | Il valore finale della tonalità, in gradi. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Ottiene il valore di saturazione iniziale.


**Returns:**
float - La saturazione varia da 0.0 a 1.0, dove 0.0 è in scala di grigi e 1.0 è la massima saturazione.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Imposta il valore di saturazione iniziale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | La saturazione varia da 0.0 a 1.0, dove 0.0 è in scala di grigi e 1.0 è la massima saturazione. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Ottiene il valore di saturazione finale.


**Returns:**
float - La saturazione varia da 0.0 a 1.0, dove 0.0 è in scala di grigi e 1.0 è la massima saturazione.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Imposta il valore di saturazione finale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | La saturazione varia da 0.0 a 1.0, dove 0.0 è in scala di grigi e 1.0 è la massima saturazione. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Ottiene il valore di luminosità iniziale.


**Returns:**
float - La luminosità varia da 0.0 a 1.0, dove 0.0 rappresenta il nero e 1.0 rappresenta il bianco.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Imposta il valore di luminosità iniziale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | La luminosità varia da 0.0 a 1.0, dove 0.0 rappresenta il nero e 1.0 rappresenta il bianco. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Ottiene il valore di luminosità finale.


**Returns:**
float - La luminosità varia da 0.0 a 1.0, dove 0.0 rappresenta il nero e 1.0 rappresenta il bianco.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Imposta il valore di luminosità finale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | La luminosità varia da 0.0 a 1.0, dove 0.0 rappresenta il nero e 1.0 rappresenta il bianco. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Ottiene un valore che indica se solo il colore vuoto è nell'intervallo.


**Returns:**
boolean - True se solo il colore vuoto è nell'intervallo (i range HSB sono ignorati); altrimenti, false.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Imposta un valore che indica se solo il colore vuoto è nell'intervallo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | True se solo il colore vuoto è nell'intervallo (i range HSB sono ignorati); altrimenti, false. |
|

