---
title: "OfficeImageFillFormat"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les paramètres du format de remplissage d'image dans tout contenu Office pris en charge."
type: docs
weight: 46
url: /fr/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Représente les paramètres du format de remplissage d'image dans tout contenu Office pris en charge.


TWatermarkableImage
: Le type exact de l'image filigrane utilisée comme arrière-plan.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Obtient une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Définit une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan. |
|
|  | [getTransparency()](#getTransparency--) | Obtient la transparence de l'image d'arrière-plan sous forme d'une valeur comprise entre 0.0 (opaque) et 1.0 (totalement transparent). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Définit la transparence de l'image d'arrière-plan sous forme d'une valeur comprise entre 0.0 (opaque) et 1.0 (totalement transparent). |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Obtient l'image d'arrière-plan. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Définit l'image d'arrière-plan. |
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


Obtient une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan.


**Returns:**
booléen - True si l'image est répétée sur l'arrière-plan ; sinon, false (l'image est étirée).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Définit une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | True si l'image est répétée sur l'arrière-plan ; sinon, false (l'image est étirée). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Obtient la transparence de l'image d'arrière-plan sous forme d'une valeur comprise entre 0.0 (opaque) et 1.0 (totalement transparent).


**Returns:**
double - La transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) jusqu'à 1.0 (totalement transparent).

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Définit la transparence de l'image d'arrière-plan sous forme d'une valeur comprise entre 0.0 (opaque) et 1.0 (totalement transparent).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) jusqu'à 1.0 (totalement transparent). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Obtient l'image d'arrière-plan.


**Returns:**
TWatermarkableImage - L'image d'arrière-plan. Retourne null si l'image n'est pas définie.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Définit l'image d'arrière-plan.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | TWatermarkableImage | L'image d'arrière-plan. Retourne null si l'image n'est pas définie. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



