---
title: "WordProcessingShapeSettings"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt instellingen weer die kunnen worden toegepast op een vormwatermerk voor een Word-document."
type: docs
weight: 71
url: /nl/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Stelt instellingen weer die kunnen worden toegepast op een vormwatermerk voor een Word-document.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Initialiseert een nieuw exemplaar van de klasse `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isLocked()](#isLocked--) | Haalt een waarde op die aangeeft of bewerken van de vorm in Word verboden is. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Stelt een waarde in die aangeeft of bewerken van de vorm in Word verboden is. |
|
|  | [getLockType()](#getLockType--) | Haalt het vergrendeltype van het watermerk op. |
|
|  | [setLockType(int value)](#setLockType-int-) | Stelt het vergrendeltype van het watermerk in. |
|
|  | [getPassword()](#getPassword--) | Haalt een wachtwoord op dat wordt gebruikt om het watermerk te vergrendelen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stelt een wachtwoord in dat wordt gebruikt om het watermerk te vergrendelen. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Haalt de paginanummers op om het watermerk toe te voegen. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Stelt de paginanummers in om het watermerk toe te voegen. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Initialiseert een nieuw exemplaar van de klasse `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`.


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Haalt een waarde op die aangeeft of bewerken van de vorm in Word verboden is.


**Returns:**
boolean - Als de waarde true is, wordt bewerken van de vorm verboden. Standaard is de waarde false, de vorm kan in Word worden bewerkt.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Stelt een waarde in die aangeeft of bewerken van de vorm in Word verboden is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | Als de waarde true is, wordt bewerken van vormen verboden. Standaard is de waarde false, kan de vorm worden bewerkt in Word. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Haalt het vergrendeltype van het watermerk op.


**Returns:**
int - Het watermerk vergrendeltype van `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Stelt het vergrendeltype van het watermerk in.

Waarde `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` kan niet worden gebruikt met
een object van het type `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | int | Het watermerk vergrendeltype van `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Haalt een wachtwoord op dat wordt gebruikt om het watermerk te vergrendelen.


**Returns:**
java.lang.String - Een wachtwoord gebruikt om het watermerk te vergrendelen.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Stelt een wachtwoord in dat wordt gebruikt om het watermerk te vergrendelen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Een wachtwoord gebruikt om het watermerk te vergrendelen. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Haalt de paginanummers op om het watermerk toe te voegen.


**Returns:**
int[] - De paginanummers om het watermerk toe te voegen.

<br />

*** ** * ** ***

Alle getallen moeten groter dan of gelijk aan 1 zijn. Deze eigenschap wordt alleen gebruikt bij het toevoegen van het watermerk aan een document. Als deze waarde null is, wordt het watermerk aan alle pagina's toegevoegd.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Stelt de paginanummers in om het watermerk toe te voegen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int[] | De paginanummers om het watermerk toe te voegen. |

<br />

*** ** * ** ***

Alle getallen moeten groter dan of gelijk aan 1 zijn. Deze eigenschap wordt alleen gebruikt bij het toevoegen van het watermerk aan een document. Als deze waarde null is, wordt het watermerk aan alle pagina's toegevoegd.

<br />

|

