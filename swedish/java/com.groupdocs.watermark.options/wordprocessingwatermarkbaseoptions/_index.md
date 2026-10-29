---
title: "WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Bas-klass för alternativ för att lägga till vattenmärke i ett Word-dokument."
type: docs
weight: 73
url: /sv/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Bas-klass för alternativ för att lägga till vattenmärke i ett Word-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isLocked()](#isLocked--) | Hämtar ett värde som indikerar om redigering av formen i Word är förbjuden. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Ställer in ett värde som indikerar om redigering av formen i Word är förbjuden. |
|
|  | [getLockType()](#getLockType--) | Hämtar vattenstämpelns låstyp. |
|
|  | [setLockType(int value)](#setLockType-int-) | Ställer in vattenstämpelns låstyp. |
|
|  | [getPassword()](#getPassword--) | Hämtar ett lösenord som används för att låsa vattenstämpeln. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ställer in ett lösenord som används för att låsa vattenstämpeln. |
|
|  | [getName()](#getName--) | Hämtar namnet på en form. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Anger namnet på en form. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Hämtar den beskrivande (alternativa) texten som kommer att associeras med en form. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Anger den beskrivande (alternativa) texten som kommer att associeras med en form. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Hämtar ett värde som indikerar om redigering av formen i Word är förbjuden.


**Returns:**
boolean - Om värdet är  true , kommer redigering av formen att vara förbjuden. Som standard är värdet  false , så kan formen redigeras i Word.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Ställer in ett värde som indikerar om redigering av formen i Word är förbjuden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Om värdet är  true , kommer formredigering att förbjudas. Som standard är värdet  false , så kan formen redigeras i Word. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Hämtar vattenstämpelns låstyp.


**Returns:**
int - Vattenstämpelns `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` låstyp.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Ställer in vattenstämpelns låstyp.

Värdet `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` kan inte användas med
ett objekt av typen `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Vattenstämpelns `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` låstyp. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar ett lösenord som används för att låsa vattenstämpeln.


**Returns:**
java.lang.String - Ett lösenord som används för att låsa vattenstämpeln.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ställer in ett lösenord som används för att låsa vattenstämpeln.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Ett lösenord som används för att låsa vattenstämpeln. |
|

### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på en form.


**Returns:**
java.lang.String - Formens namn.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Anger namnet på en form.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Formens namn. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Hämtar den beskrivande (alternativa) texten som kommer att associeras med en form.


**Returns:**
java.lang.String - Den beskrivande (alternativa) texten som kommer att associeras med en form.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Anger den beskrivande (alternativa) texten som kommer att associeras med en form.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Den beskrivande (alternativa) texten som kommer att associeras med en form. |
|

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

