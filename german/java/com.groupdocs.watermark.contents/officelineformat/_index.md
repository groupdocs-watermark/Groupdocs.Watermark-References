---
title: "OfficeLineFormat"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Formlinienformat dar."
type: docs
weight: 47
url: /de/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Stellt ein Formlinienformat dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | Initialisiert eine neue Instanz der `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`-Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWeight()](#getWeight--) | Ruft die Pinselstärke ab, die den Pfad einer Form nachzeichnet. |
|
|  | [setWeight(double value)](#setWeight-double-) | Legt die Pinselstärke fest, die den Pfad einer Form nachzeichnet. |
|
|  | [getColor()](#getColor--) | Ruft die Farbe der Linie ab. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Legt die Farbe der Linie fest. |
|
|  | [getOpacity()](#getOpacity--) | Ruft die Deckkraft der Linie ab. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Legt die Deckkraft der Linie fest. |
|
|  | [getEnabled()](#getEnabled--) | Ruft einen Wert ab, der angibt, ob eine Form nachgezeichnet wird. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | Legt einen Wert fest, der angibt, ob eine Form nachgezeichnet wird. |
|
|  | [getDashStyle()](#getDashStyle--) | Ruft das Punkt- und Strichmuster für eine Linie ab. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Legt das Punkt- und Strichmuster für eine Linie fest. |
|
|  | [getLineStyle()](#getLineStyle--) | Ruft den Linienstil ab. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | Legt den Linienstil fest. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Initialisiert eine neue Instanz der `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`-Klasse.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


Ruft die Pinselstärke ab, die den Pfad einer Form nachzeichnet.


**Returns:**
double - Die Linienstärke in Punkten. Der Standardwert ist 0.75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Legt die Pinselstärke fest, die den Pfad einer Form nachzeichnet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die Linienstärke in Punkten. Der Standardwert ist 0.75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Ruft die Farbe der Linie ab.

Der Standardwert ist `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Legt die Farbe der Linie fest.

Der Standardwert ist `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Die Farbe der Linie. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Ruft die Deckkraft der Linie ab.


**Returns:**
double - Der Wert sollte zwischen 0 und 1 liegen. Der Standardwert ist 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Legt die Deckkraft der Linie fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Der Wert sollte zwischen 0 und 1 liegen. Der Standardwert ist 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Ruft einen Wert ab, der angibt, ob eine Form nachgezeichnet wird.


**Returns:**
boolescher Wert – Der Standardwert ist false.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Legt einen Wert fest, der angibt, ob eine Form nachgezeichnet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Der Standardwert ist false. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Ruft das Punkt- und Strichmuster für eine Linie ab.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Legt das Punkt- und Strichmuster für eine Linie fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Ruft den Linienstil ab.

Der Standardwert ist `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Returns:**
int - Der Linienstil.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Legt den Linienstil fest.

Der Standardwert ist `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Linienstil. |
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
