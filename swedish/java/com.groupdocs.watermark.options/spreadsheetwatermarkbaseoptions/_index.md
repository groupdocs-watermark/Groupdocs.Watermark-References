---
title: "SpreadsheetWatermarkBaseOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Bas-klass för alternativ för att lägga till vattenstämpel i ett Spreadsheet-dokument."
type: docs
weight: 56
url: /sv/java/com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public abstract class SpreadsheetWatermarkBaseOptions extends SpreadsheetWatermarkOptions
```

Bas-klass för alternativ för att lägga till vattenstämpel i ett Spreadsheet-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isLocked()](#isLocked--) | Hämtar ett värde som indikerar om redigering av formen i Excel är förbjuden. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Anger ett värde som indikerar om redigering av formen i Excel är förbjuden. |
|
|  | [getName()](#getName--) | Hämtar namnet på en form. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Anger namnet på en form. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Hämtar den beskrivande (alternativa) texten som kommer att associeras med en form. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Anger den beskrivande (alternativa) texten som kommer att associeras med en form. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Hämtar ett värde som indikerar om redigering av formen i Excel är förbjuden.


**Returns:**
boolean - Om värdet är true, kommer redigering av formen att vara förbjuden. Som standard är värdet false, så formen kan redigeras i Excel.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Anger ett värde som indikerar om redigering av formen i Excel är förbjuden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Om värdet är true, kommer redigering av formen att vara förbjuden. Som standard är värdet false, så formen kan redigeras i Excel. |
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

