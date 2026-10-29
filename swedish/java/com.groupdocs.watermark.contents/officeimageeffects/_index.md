---
title: "OfficeImageEffects"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar effekter som kan tillämpas på en bildvattenstämpel för ett office‑innehåll."
type: docs
weight: 45
url: /sv/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

Representerar effekter som kan tillämpas på en bildvattenstämpel för ett office‑innehåll.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | Hämtar linjeformatinställningar för bildramen. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | Ställer in linjeformatinställningar för bildramen. |
|
|  | [getGrayScale()](#getGrayScale--) | Hämtar ett värde som indikerar om en bild ska visas i gråskala. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | Ställer in ett värde som indikerar om en bild ska visas i gråskala. |
|
|  | [getChromaKey()](#getChromaKey--) | Hämtar färgvärdet för bilden som kommer att behandlas som transparent. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | Ställer in färgvärdet för bilden som kommer att behandlas som transparent. |
|
|  | [getBrightness()](#getBrightness--) | Hämtar bildens ljusstyrka. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | Ställer in bildens ljusstyrka. |
|
|  | [getContrast()](#getContrast--) | Hämtar kontrasten för den angivna bilden. |
|
|  | [setContrast(double value)](#setContrast-double-) | Ställer in kontrasten för den angivna bilden. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


Hämtar linjeformatinställningar för bildramen.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


Ställer in linjeformatinställningar för bildramen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | Instans av  OfficeLineFormat  klass, som representerar formens linjeformat. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


Hämtar ett värde som indikerar om en bild ska visas i gråskala.


**Returns:**
boolean - Standardvärdet är falskt.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


Ställer in ett värde som indikerar om en bild ska visas i gråskala.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Standardvärdet är falskt. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


Hämtar färgvärdet för bilden som kommer att behandlas som transparent.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


Ställer in färgvärdet för bilden som kommer att behandlas som transparent.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Standardvärdet är en helt genomskinlig färg. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Hämtar bildens ljusstyrka. Värdet för denna egenskap måste
vara ett tal mellan 0,0 (mörkast) och 1,0 (ljusast).


**Returns:**
double - Standardvärdet är 0,5.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Ställer in bildens ljusstyrka. Värdet för denna egenskap måste
vara ett tal mellan 0,0 (mörkast) och 1,0 (ljusast).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Standardvärdet är 0,5. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


Hämtar kontrasten för den angivna bilden. Värdet för denna egenskap
måste vara ett tal mellan 0,0 (minsta kontrast) och 1,0 (största kontrast).


**Returns:**
double - Standardvärdet är 0,5.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


Ställer in kontrasten för den angivna bilden. Värdet för denna egenskap
måste vara ett tal mellan 0,0 (minsta kontrast) och 1,0 (största kontrast).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Standardvärdet är 0,5. |
|

