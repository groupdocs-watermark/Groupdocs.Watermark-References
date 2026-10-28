---
title: "OfficeLineFormat"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un format de ligne de forme."
type: docs
weight: 47
url: /fr/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Représente un format de ligne de forme.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | Initialise une nouvelle instance de la classe `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWeight()](#getWeight--) | Obtient l'épaisseur du pinceau qui trace le chemin d'une forme. |
|
|  | [setWeight(double value)](#setWeight-double-) | Définit l'épaisseur du pinceau qui trace le chemin d'une forme. |
|
|  | [getColor()](#getColor--) | Obtient la couleur de la ligne. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Définit la couleur de la ligne. |
|
|  | [getOpacity()](#getOpacity--) | Obtient l'opacité de la ligne. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Définit l'opacité de la ligne. |
|
|  | [getEnabled()](#getEnabled--) | Obtient une valeur indiquant si une forme sera tracée. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | Définit une valeur indiquant si une forme sera tracée. |
|
|  | [getDashStyle()](#getDashStyle--) | Obtient le motif point-tiret d'une ligne. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Définit le motif point-tiret d'une ligne. |
|
|  | [getLineStyle()](#getLineStyle--) | Obtient le style de ligne. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | Définit le style de ligne. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Initialise une nouvelle instance de la classe `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


Obtient l'épaisseur du pinceau qui trace le chemin d'une forme.


**Returns:**
double - L'épaisseur de la ligne en points. La valeur par défaut est 0,75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Définit l'épaisseur du pinceau qui trace le chemin d'une forme.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | L'épaisseur de la ligne en points. La valeur par défaut est 0,75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Obtient la couleur de la ligne.

La valeur par défaut est `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Définit la couleur de la ligne.

La valeur par défaut est `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur de la ligne. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Obtient l'opacité de la ligne.


**Returns:**
double - La valeur doit être comprise entre 0 et 1. La valeur par défaut est 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Définit l'opacité de la ligne.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La valeur doit être comprise entre 0 et 1. La valeur par défaut est 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Obtient une valeur indiquant si une forme sera tracée.


**Returns:**
booléen - La valeur par défaut est false.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Définit une valeur indiquant si une forme sera tracée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | La valeur par défaut est false. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Obtient le motif point-tiret d'une ligne.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Définit le motif point-tiret d'une ligne.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Obtient le style de ligne.

La valeur par défaut est `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Returns:**
int - Le style de ligne.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Définit le style de ligne.

La valeur par défaut est `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Le style de ligne. |
|

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


<br />



**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```


<br />



**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
