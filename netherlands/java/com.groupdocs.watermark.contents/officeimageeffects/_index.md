---
title: "OfficeImageEffects"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt effecten voor die op een afbeeldingswatermerk voor een Office-inhoud kunnen worden toegepast."
type: docs
weight: 45
url: /nl/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

Stelt effecten voor die op een afbeeldingswatermerk voor een Office-inhoud kunnen worden toegepast.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | Haalt een lijnformaatinstelling op voor de rand van de afbeelding. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | Stelt een lijnformaatinstelling in voor de rand van de afbeelding. |
|
|  | [getGrayScale()](#getGrayScale--) | Haalt een waarde op die aangeeft of een afbeelding in grijstintenmodus wordt weergegeven. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | Stelt een waarde in die aangeeft of een afbeelding in grijstintenmodus wordt weergegeven. |
|
|  | [getChromaKey()](#getChromaKey--) | Haalt de kleurwaarde van de afbeelding op die als transparant wordt behandeld. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | Stelt de kleurwaarde van de afbeelding in die als transparant wordt behandeld. |
|
|  | [getBrightness()](#getBrightness--) | Haalt de helderheid van de afbeelding op. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | Stelt de helderheid van de afbeelding in. |
|
|  | [getContrast()](#getContrast--) | Haalt het contrast op voor de opgegeven afbeelding. |
|
|  | [setContrast(double value)](#setContrast-double-) | Stelt het contrast in voor de opgegeven afbeelding. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


Haalt een lijnformaatinstelling op voor de rand van de afbeelding.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


Stelt een lijnformaatinstelling in voor de rand van de afbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | Instantie van de OfficeLineFormat-klasse, die het lijnformaat van een vorm vertegenwoordigt. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


Haalt een waarde op die aangeeft of een afbeelding in grijstintenmodus wordt weergegeven.


**Returns:**
boolean - De standaardwaarde is false.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


Stelt een waarde in die aangeeft of een afbeelding in grijstintenmodus wordt weergegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | De standaardwaarde is false. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


Haalt de kleurwaarde van de afbeelding op die als transparant wordt behandeld.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


Stelt de kleurwaarde van de afbeelding in die als transparant wordt behandeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | De standaardwaarde is volledig transparante kleur. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Haalt de helderheid van de afbeelding op. De waarde voor deze eigenschap moet
een getal zijn van 0,0 (donkerst) tot 1,0 (helderst).


**Returns:**
double - De standaardwaarde is 0,5.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Stelt de helderheid van de afbeelding in. De waarde voor deze eigenschap moet
een getal zijn van 0,0 (donkerst) tot 1,0 (helderst).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De standaardwaarde is 0,5. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


Haalt het contrast op voor de opgegeven afbeelding. De waarde voor deze eigenschap
moet een getal zijn van 0.0 (het minste contrast) tot 1.0 (het grootste contrast).


**Returns:**
double - De standaardwaarde is 0,5.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


Stelt het contrast in voor de opgegeven afbeelding. De waarde voor deze eigenschap
moet een getal zijn van 0.0 (het minste contrast) tot 1.0 (het grootste contrast).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De standaardwaarde is 0,5. |
|

