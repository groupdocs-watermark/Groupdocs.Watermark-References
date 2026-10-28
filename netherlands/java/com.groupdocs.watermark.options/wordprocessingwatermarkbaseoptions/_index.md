---
title: "WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Basisklasse voor opties voor het toevoegen van watermerken aan een Word-document."
type: docs
weight: 73
url: /nl/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Basisklasse voor opties voor het toevoegen van watermerken aan een Word-document.

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
|  | [getName()](#getName--) | Haalt de naam van een vorm op. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Stelt de naam van een vorm in. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Haalt de beschrijvende (alternatieve) tekst op die aan een vorm zal worden gekoppeld. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Stelt de beschrijvende (alternatieve) tekst in die aan een vorm zal worden gekoppeld. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
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
int - Het watermerk `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` vergrendeltype.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Stelt het vergrendeltype van het watermerk in.

De waarde `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` kan niet worden gebruikt met
een object van het type `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | int | Het watermerk `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` vergrendeltype. |
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

### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van een vorm op.


**Returns:**
java.lang.String - De vormnaam.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Stelt de naam van een vorm in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De vormnaam. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Haalt de beschrijvende (alternatieve) tekst op die aan een vorm zal worden gekoppeld.


**Returns:**
java.lang.String - De beschrijvende (alternatieve) tekst die aan een vorm zal worden gekoppeld.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Stelt de beschrijvende (alternatieve) tekst in die aan een vorm zal worden gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De beschrijvende (alternatieve) tekst die aan een vorm zal worden gekoppeld. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

