---
title: "WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Basisklasse für Optionen zum Hinzufügen von Wasserzeichen zu einem Word-Dokument."
type: docs
weight: 73
url: /de/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Basisklasse für Optionen zum Hinzufügen von Wasserzeichen zu einem Word-Dokument.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isLocked()](#isLocked--) | Gibt einen Wert zurück, der angibt, ob das Bearbeiten der Form in Word verboten ist. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Setzt einen Wert, der angibt, ob das Bearbeiten der Form in Word verboten ist. |
|
|  | [getLockType()](#getLockType--) | Gibt den Sperrtyp des Wasserzeichens zurück. |
|
|  | [setLockType(int value)](#setLockType-int-) | Setzt den Sperrtyp des Wasserzeichens. |
|
|  | [getPassword()](#getPassword--) | Gibt ein Passwort zurück, das zum Sperren des Wasserzeichens verwendet wird. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Setzt ein Passwort, das zum Sperren des Wasserzeichens verwendet wird. |
|
|  | [getName()](#getName--) | Liefert den Namen einer Form. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Setzt den Namen einer Form. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Liefert den beschreibenden (alternativen) Text, der einer Form zugeordnet wird. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Setzt den beschreibenden (alternativen) Text, der einer Form zugeordnet wird. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Gibt einen Wert zurück, der angibt, ob das Bearbeiten der Form in Word verboten ist.


**Returns:**
boolean - Wenn der Wert true ist, wird das Bearbeiten der Form verboten. Standardmäßig ist der Wert false, die Form kann in Word bearbeitet werden.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Setzt einen Wert, der angibt, ob das Bearbeiten der Form in Word verboten ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Wenn der Wert true ist, wird die Formbearbeitung verboten. Standardmäßig ist der Wert false, die Form kann in Word bearbeitet werden. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Gibt den Sperrtyp des Wasserzeichens zurück.


**Returns:**
int - Der Wasserzeichen `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` Sperrtyp.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Setzt den Sperrtyp des Wasserzeichens.

Der Wert `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` kann nicht verwendet werden mit
einem Objekt vom Typ `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Der Wasserzeichen `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` Sperrtyp. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gibt ein Passwort zurück, das zum Sperren des Wasserzeichens verwendet wird.


**Returns:**
java.lang.String - Ein Passwort, das zum Sperren des Wasserzeichens verwendet wird.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Setzt ein Passwort, das zum Sperren des Wasserzeichens verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Ein Passwort, das zum Sperren des Wasserzeichens verwendet wird. |
|

### getName() {#getName--}
```
public final String getName()
```


Liefert den Namen einer Form.


**Returns:**
java.lang.String - Der Name der Form.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Setzt den Namen einer Form.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Name der Form. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Liefert den beschreibenden (alternativen) Text, der einer Form zugeordnet wird.


**Returns:**
java.lang.String - Der beschreibende (alternative) Text, der mit einer Form verknüpft wird.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Setzt den beschreibenden (alternativen) Text, der einer Form zugeordnet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der beschreibende (alternative) Text, der mit einer Form verknüpft wird. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

