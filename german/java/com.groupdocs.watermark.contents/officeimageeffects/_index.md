---
title: "OfficeImageEffects"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Effekte dar, die auf ein Bildwasserzeichen für Office-Inhalte angewendet werden können."
type: docs
weight: 45
url: /de/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

Stellt Effekte dar, die auf ein Bildwasserzeichen für Office-Inhalte angewendet werden können.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | Ruft die Einstellungen des Linienformats für den Bildrahmen ab. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | Legt die Einstellungen des Linienformats für den Bildrahmen fest. |
|
|  | [getGrayScale()](#getGrayScale--) | Ruft einen Wert ab, der angibt, ob ein Bild im Graustufenmodus angezeigt wird. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | Legt einen Wert fest, der angibt, ob ein Bild im Graustufenmodus angezeigt wird. |
|
|  | [getChromaKey()](#getChromaKey--) | Ruft den Farbwert des Bildes ab, der als transparent behandelt wird. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | Legt den Farbwert des Bildes fest, der als transparent behandelt wird. |
|
|  | [getBrightness()](#getBrightness--) | Ruft die Helligkeit des Bildes ab. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | Legt die Helligkeit des Bildes fest. |
|
|  | [getContrast()](#getContrast--) | Ruft den Kontrast für das angegebene Bild ab. |
|
|  | [setContrast(double value)](#setContrast-double-) | Legt den Kontrast für das angegebene Bild fest. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


Ruft die Einstellungen des Linienformats für den Bildrahmen ab.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


Legt die Einstellungen des Linienformats für den Bildrahmen fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | Instanz der Klasse OfficeLineFormat, die das Linienformat einer Form darstellt. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


Ruft einen Wert ab, der angibt, ob ein Bild im Graustufenmodus angezeigt wird.


**Returns:**
boolescher Wert – Der Standardwert ist false.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


Legt einen Wert fest, der angibt, ob ein Bild im Graustufenmodus angezeigt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Der Standardwert ist false. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


Ruft den Farbwert des Bildes ab, der als transparent behandelt wird.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


Legt den Farbwert des Bildes fest, der als transparent behandelt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Der Standardwert ist vollständig transparente Farbe. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Ruft die Helligkeit des Bildes ab. Der Wert für diese Eigenschaft muss
eine Zahl zwischen 0,0 (dunkelste) und 1,0 (hellste) sein.


**Returns:**
double - Der Standardwert ist 0,5.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Setzt die Helligkeit des Bildes. Der Wert für diese Eigenschaft muss
eine Zahl zwischen 0,0 (dunkelste) und 1,0 (hellste) sein.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Der Standardwert ist 0,5. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


Liest den Kontrast des angegebenen Bildes. Der Wert für diese Eigenschaft
muss eine Zahl von 0,0 (geringster Kontrast) bis 1,0 (höchster Kontrast) sein.


**Returns:**
double - Der Standardwert ist 0,5.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


Setzt den Kontrast des angegebenen Bildes. Der Wert für diese Eigenschaft
muss eine Zahl von 0,0 (geringster Kontrast) bis 1,0 (höchster Kontrast) sein.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Der Standardwert ist 0,5. |
|

