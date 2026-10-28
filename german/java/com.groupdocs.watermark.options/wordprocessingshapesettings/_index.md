---
title: "WordProcessingShapeSettings"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Einstellungen dar, die auf ein Formwasserzeichen für ein Word-Dokument angewendet werden können."
type: docs
weight: 71
url: /de/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Stellt Einstellungen dar, die auf ein Formwasserzeichen für ein Word-Dokument angewendet werden können.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Initialisiert eine neue Instanz der `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` Klasse. |
|
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
|  | [getPageNumbers()](#getPageNumbers--) | Ermittelt die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Setzt die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Initialisiert eine neue Instanz der `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` Klasse.


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
int - Der Wasserzeichen‑Sperrtyp von `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

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
|  | value | int | Der Wasserzeichen‑Sperrtyp von `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
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

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Ermittelt die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int[] - Die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll.

<br />

*** ** * ** ***

Alle Zahlen müssen größer oder gleich 1 sein. Diese Eigenschaft wird nur beim Hinzufügen des Wasserzeichens zu einem Dokument verwendet. Wenn dieser Wert null ist, wird das Wasserzeichen zu allen Seiten hinzugefügt.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Setzt die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int[] | Die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll. |

<br />

*** ** * ** ***

Alle Zahlen müssen größer oder gleich 1 sein. Diese Eigenschaft wird nur beim Hinzufügen des Wasserzeichens zu einem Dokument verwendet. Wenn dieser Wert null ist, wird das Wasserzeichen zu allen Seiten hinzugefügt.

<br />

|

