---
title: "OfficeLineFormat"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar ett formlinjeformat."
type: docs
weight: 47
url: /sv/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Representerar ett formlinjeformat.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | Initierar en ny instans av klassen `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWeight()](#getWeight--) | Hämtar penselns tjocklek som ritar banan för en form. |
|
|  | [setWeight(double value)](#setWeight-double-) | Ställer in penselns tjocklek som ritar banan för en form. |
|
|  | [getColor()](#getColor--) | Hämtar linjens färg. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Ställer in linjens färg. |
|
|  | [getOpacity()](#getOpacity--) | Hämtar linjens opacitet. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Ställer in linjens opacitet. |
|
|  | [getEnabled()](#getEnabled--) | Hämtar ett värde som indikerar om en form kommer att kontureras. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | Ställer in ett värde som indikerar om en form kommer att kontureras. |
|
|  | [getDashStyle()](#getDashStyle--) | Hämtar punkt- och streckmönstret för en linje. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Ställer in punkt- och streckmönstret för en linje. |
|
|  | [getLineStyle()](#getLineStyle--) | Hämtar linjestilen. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | Ställer in linjestilen. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Initierar en ny instans av klassen `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


Hämtar penselns tjocklek som ritar banan för en form.


**Returns:**
double - Linjetjockleken i punkter. Standardvärdet är 0.75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Ställer in penselns tjocklek som ritar banan för en form.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Linjetjockleken i punkter. Standardvärdet är 0.75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Hämtar linjens färg.

Standardvärdet är `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Ställer in linjens färg.

Standardvärdet är `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Färgen på linjen. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Hämtar linjens opacitet.


**Returns:**
double - Värdet bör vara mellan 0 och 1. Standardvärdet är 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Ställer in linjens opacitet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Värdet bör vara mellan 0 och 1. Standardvärdet är 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Hämtar ett värde som indikerar om en form kommer att kontureras.


**Returns:**
boolean - Standardvärdet är falskt.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Ställer in ett värde som indikerar om en form kommer att kontureras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Standardvärdet är falskt. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Hämtar punkt- och streckmönstret för en linje.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Ställer in punkt- och streckmönstret för en linje.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Hämtar linjestilen.

Standardvärdet är `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Returns:**
int - Linjestilen.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Ställer in linjestilen.

Standardvärdet är `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Linjestilen. |
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
