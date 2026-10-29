---
title: "WordProcessingShapeSettings"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar inställningar som kan tillämpas på en formvattenstämpel för ett Word-dokument."
type: docs
weight: 71
url: /sv/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Representerar inställningar som kan tillämpas på en formvattenstämpel för ett Word-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Initierar en ny instans av klassen `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`. |
|
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
|  | [getPageNumbers()](#getPageNumbers--) | Hämtar sidnumren för att lägga till vattenstämpeln. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Ställer in sidnumren för att lägga till vattenstämpeln. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Initierar en ny instans av klassen `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`.


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
int - Vattenstämpelns låstyp för `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

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
|  | value | int | Vattenstämpelns låstyp för `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
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

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Hämtar sidnumren för att lägga till vattenstämpeln.


**Returns:**
int[] - Sidnumren för att lägga till vattenstämpeln.

<br />

*** ** * ** ***

Alla tal måste vara större än eller lika med 1. Denna egenskap används endast när vattenstämpeln läggs till i ett dokument. Om detta värde är  null , läggs vattenstämpeln till på alla sidor.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Ställer in sidnumren för att lägga till vattenstämpeln.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int[] | Sidnumren för att lägga till vattenstämpeln. |

<br />

*** ** * ** ***

Alla tal måste vara större än eller lika med 1. Denna egenskap används endast när vattenstämpeln läggs till i ett dokument. Om detta värde är  null , läggs vattenstämpeln till på alla sidor.

<br />

|

