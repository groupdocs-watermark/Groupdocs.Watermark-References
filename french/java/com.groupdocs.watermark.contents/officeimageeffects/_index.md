---
title: "OfficeImageEffects"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les effets qui peuvent être appliqués à un filigrane d'image pour un contenu Office."
type: docs
weight: 45
url: /fr/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

Représente les effets qui peuvent être appliqués à un filigrane d'image pour un contenu Office.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | Obtient les paramètres de format de ligne pour la bordure de l'image. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | Définit les paramètres de format de ligne pour la bordure de l'image. |
|
|  | [getGrayScale()](#getGrayScale--) | Obtient une valeur indiquant si une image sera affichée en mode niveaux de gris. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | Définit une valeur indiquant si une image sera affichée en mode niveaux de gris. |
|
|  | [getChromaKey()](#getChromaKey--) | Obtient la valeur de couleur de l'image qui sera traitée comme transparente. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | Définit la valeur de couleur de l'image qui sera traitée comme transparente. |
|
|  | [getBrightness()](#getBrightness--) | Obtient la luminosité de l'image. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | Définit la luminosité de l'image. |
|
|  | [getContrast()](#getContrast--) | Obtient le contraste de l'image spécifiée. |
|
|  | [setContrast(double value)](#setContrast-double-) | Définit le contraste de l'image spécifiée. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


Obtient les paramètres de format de ligne pour la bordure de l'image.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


Définit les paramètres de format de ligne pour la bordure de l'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | Instance de la classe OfficeLineFormat, représentant le format de ligne de forme. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


Obtient une valeur indiquant si une image sera affichée en mode niveaux de gris.


**Returns:**
booléen - La valeur par défaut est false.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


Définit une valeur indiquant si une image sera affichée en mode niveaux de gris.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | La valeur par défaut est false. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


Obtient la valeur de couleur de l'image qui sera traitée comme transparente.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


Définit la valeur de couleur de l'image qui sera traitée comme transparente.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | La valeur par défaut est une couleur entièrement transparente. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Obtient la luminosité de l'image. La valeur de cette propriété doit
être un nombre compris entre 0,0 (le plus sombre) et 1,0 (le plus lumineux).


**Returns:**
double - La valeur par défaut est 0,5.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Définit la luminosité de l'image. La valeur de cette propriété doit
être un nombre compris entre 0,0 (le plus sombre) et 1,0 (le plus lumineux).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La valeur par défaut est 0,5. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


Obtient le contraste de l'image spécifiée. La valeur de cette propriété
doit être un nombre compris entre 0,0 (le contraste le plus faible) et 1,0 (le contraste le plus élevé).


**Returns:**
double - La valeur par défaut est 0,5.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


Définit le contraste pour l'image spécifiée. La valeur de cette propriété
doit être un nombre compris entre 0,0 (le contraste le plus faible) et 1,0 (le contraste le plus élevé).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La valeur par défaut est 0,5. |
|

