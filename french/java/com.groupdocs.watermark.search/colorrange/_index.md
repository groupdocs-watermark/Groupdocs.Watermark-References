---
title: "ColorRange"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une gamme de couleurs."
type: docs
weight: 12
url: /fr/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Représente une plage de couleurs. Spécifie les plages en utilisant la représentation HSB de la couleur RVB.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | Initialise une nouvelle instance de la classe `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Initialise une nouvelle instance de la classe `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` avec une couleur exacte spécifiée. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | Obtient la valeur de teinte de départ, en degrés. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | Définit la valeur de teinte de départ, en degrés. |
|
|  | [getMaxHue()](#getMaxHue--) | Obtient la valeur de teinte finale, en degrés. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | Définit la valeur de teinte finale, en degrés. |
|
|  | [getMinSaturation()](#getMinSaturation--) | Obtient la valeur de saturation de départ. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | Définit la valeur de saturation de départ. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | Obtient la valeur de saturation finale. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | Définit la valeur de saturation finale. |
|
|  | [getMinBrightness()](#getMinBrightness--) | Obtient la valeur de luminosité de départ. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | Définit la valeur de luminosité de départ. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | Obtient la valeur de luminosité finale. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | Définit la valeur de luminosité finale. |
|
|  | [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si seule la couleur vide est dans la plage. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | Définit une valeur indiquant si seule la couleur vide est dans la plage. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Initialise une nouvelle instance de la classe `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Initialise une nouvelle instance de la classe `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` avec une couleur exacte spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur exacte à partir de laquelle la plage est créée. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Obtient la valeur de teinte de départ, en degrés.


**Returns:**
float - La valeur de teinte de départ, en degrés.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Définit la valeur de teinte de départ, en degrés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | La valeur de teinte de départ, en degrés. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Obtient la valeur de teinte finale, en degrés.


**Returns:**
float - La valeur de teinte finale, en degrés.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Définit la valeur de teinte finale, en degrés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | La valeur de teinte finale, en degrés. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Obtient la valeur de saturation de départ.


**Returns:**
float - La saturation varie de 0.0 à 1.0, où 0.0 correspond à l'échelle de gris et 1.0 à la saturation maximale.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Définit la valeur de saturation de départ.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | La saturation varie de 0.0 à 1.0, où 0.0 correspond à l'échelle de gris et 1.0 à la saturation maximale. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Obtient la valeur de saturation finale.


**Returns:**
float - La saturation varie de 0.0 à 1.0, où 0.0 correspond à l'échelle de gris et 1.0 à la saturation maximale.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Définit la valeur de saturation finale.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | La saturation varie de 0.0 à 1.0, où 0.0 correspond à l'échelle de gris et 1.0 à la saturation maximale. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Obtient la valeur de luminosité de départ.


**Returns:**
float - La luminosité varie de 0.0 à 1.0, où 0.0 représente le noir et 1.0 représente le blanc.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Définit la valeur de luminosité de départ.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | La luminosité varie de 0.0 à 1.0, où 0.0 représente le noir et 1.0 représente le blanc. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Obtient la valeur de luminosité finale.


**Returns:**
float - La luminosité varie de 0.0 à 1.0, où 0.0 représente le noir et 1.0 représente le blanc.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Définit la valeur de luminosité finale.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | La luminosité varie de 0.0 à 1.0, où 0.0 représente le noir et 1.0 représente le blanc. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtient une valeur indiquant si seule la couleur vide est dans la plage.


**Returns:**
boolean - Vrai si seule la couleur vide est dans la plage (les plages HSB sont ignorées) ; sinon, faux.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Définit une valeur indiquant si seule la couleur vide est dans la plage.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Vrai si seule la couleur vide est dans la plage (les plages HSB sont ignorées) ; sinon, faux. |
|

