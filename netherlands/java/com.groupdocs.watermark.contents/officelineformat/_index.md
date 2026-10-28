---
title: "OfficeLineFormat"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een vormlijnformaat voor."
type: docs
weight: 47
url: /nl/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Stelt een vormlijnformaat voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | Initialiseert een nieuw exemplaar van de klasse `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWeight()](#getWeight--) | Haalt de penseeldikte op die de omtrek van een vorm tekent. |
|
|  | [setWeight(double value)](#setWeight-double-) | Stelt de penseeldikte in die de omtrek van een vorm tekent. |
|
|  | [getColor()](#getColor--) | Haalt de kleur van de lijn op. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Stelt de kleur van de lijn in. |
|
|  | [getOpacity()](#getOpacity--) | Haalt de doorzichtigheid van de lijn op. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Stelt de doorzichtigheid van de lijn in. |
|
|  | [getEnabled()](#getEnabled--) | Haalt een waarde op die aangeeft of een vorm een omtrek krijgt. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | Stelt een waarde in die aangeeft of een vorm een omtrek krijgt. |
|
|  | [getDashStyle()](#getDashStyle--) | Haalt het stip- en streeppatroon voor een lijn op. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Stelt het stip- en streeppatroon voor een lijn in. |
|
|  | [getLineStyle()](#getLineStyle--) | Haalt de lijnstijl op. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | Stelt de lijnstijl in. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Initialiseert een nieuw exemplaar van de klasse `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


Haalt de penseeldikte op die de omtrek van een vorm tekent.


**Returns:**
double - De lijndikte in punten. De standaardwaarde is 0,75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Stelt de penseeldikte in die de omtrek van een vorm tekent.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De lijndikte in punten. De standaardwaarde is 0,75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Haalt de kleur van de lijn op.

De standaardwaarde is `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Stelt de kleur van de lijn in.

De standaardwaarde is `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | De kleur van de lijn. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Haalt de doorzichtigheid van de lijn op.


**Returns:**
double - De waarde moet tussen 0 en 1 liggen. Standaardwaarde is 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Stelt de doorzichtigheid van de lijn in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De waarde moet tussen 0 en 1 liggen. Standaardwaarde is 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Haalt een waarde op die aangeeft of een vorm een omtrek krijgt.


**Returns:**
boolean - De standaardwaarde is false.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Stelt een waarde in die aangeeft of een vorm een omtrek krijgt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | De standaardwaarde is false. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Haalt het stip- en streeppatroon voor een lijn op.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Stelt het stip- en streeppatroon voor een lijn in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Haalt de lijnstijl op.

De standaardwaarde is `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Returns:**
int - De lijnstijl.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Stelt de lijnstijl in.

De standaardwaarde is `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De lijnstijl. |
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
