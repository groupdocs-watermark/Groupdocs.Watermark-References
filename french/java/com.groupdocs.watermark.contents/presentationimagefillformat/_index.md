---
title: "PresentationImageFillFormat"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les paramètres de format de remplissage d'image dans un document PowerPoint."
type: docs
weight: 85
url: /fr/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

Représente les paramètres de format de remplissage d'image dans un document PowerPoint.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Obtient une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Définit une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan. |
|
|  | [getTransparency()](#getTransparency--) | Obtient la transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) à 1.0 |
(totalement transparent).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Définit la transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) à 1.0 |
(totalement transparent).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Obtient l'image d'arrière-plan. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Définit l'image d'arrière-plan. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Obtient une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan.


**Returns:**
booléen - Vrai si l'image est répétée sur l'arrière-plan ; sinon, false (l'image est étirée). La valeur par défaut est false.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Définit une valeur indiquant si l'image est répétée en mosaïque sur l'arrière-plan.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Vrai si l'image est répétée sur l'arrière-plan ; sinon, false (l'image est étirée). La valeur par défaut est false. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Obtient la transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) à 1.0
(totalement transparent).


**Returns:**
double - La transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) jusqu'à 1.0 (totalement transparent).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Définit la transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) à 1.0
(totalement transparent).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La transparence de l'image d'arrière-plan sous forme d'une valeur de 0.0 (opaque) jusqu'à 1.0 (totalement transparent). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Obtient l'image d'arrière-plan.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Définit l'image d'arrière-plan.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | L'image d'arrière-plan. Retourne null si l'image n'est pas définie. |
|

