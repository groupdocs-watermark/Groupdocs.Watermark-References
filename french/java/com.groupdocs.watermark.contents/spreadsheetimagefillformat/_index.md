---
title: "SpreadsheetImageFillFormat"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les paramètres de format de remplissage d'image dans un document Excel."
type: docs
weight: 114
url: /fr/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Représente les paramètres de format de remplissage d'image dans un document Excel.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Obtient une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Définit une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan. |
|
|  | [getTransparency()](#getTransparency--) | Obtient la transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) |
jusqu'à 1.0 (totalement transparent).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Définit la transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) |
jusqu'à 1.0 (totalement transparent).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Obtient l'image d'arrière-plan. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Définit l'image d'arrière-plan. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Obtient une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan.


**Returns:**
booléen - True si l'image est répétée sur l'arrière-plan ; sinon, false (l'image est étirée).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Définit une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | True si l'image est répétée sur l'arrière-plan ; sinon, false (l'image est étirée). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Obtient la transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque)
jusqu'à 1.0 (totalement transparent).


**Returns:**
double - La transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) jusqu'à 1.0 (totalement transparent).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Définit la transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque)
jusqu'à 1.0 (totalement transparent).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) jusqu'à 1.0 (totalement transparent). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Obtient l'image d'arrière-plan.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Définit l'image d'arrière-plan.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | L'image d'arrière-plan. Retourne null si l'image n'est pas définie. |
|

