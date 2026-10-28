---
title: "SpreadsheetWatermarkBaseOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Basisklasse für Optionen zum Hinzufügen von Wasserzeichen zu einem Kalkulationstabellendokument."
type: docs
weight: 56
url: /de/java/com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public abstract class SpreadsheetWatermarkBaseOptions extends SpreadsheetWatermarkOptions
```

Basisklasse für Optionen zum Hinzufügen von Wasserzeichen zu einem Kalkulationstabellendokument.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isLocked()](#isLocked--) | Liefert einen Wert, der angibt, ob die Bearbeitung der Form in Excel verboten ist. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Setzt einen Wert, der angibt, ob die Bearbeitung der Form in Excel verboten ist. |
|
|  | [getName()](#getName--) | Liefert den Namen einer Form. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Setzt den Namen einer Form. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Liefert den beschreibenden (alternativen) Text, der einer Form zugeordnet wird. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Setzt den beschreibenden (alternativen) Text, der einer Form zugeordnet wird. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Liefert einen Wert, der angibt, ob die Bearbeitung der Form in Excel verboten ist.


**Returns:**
boolean - Wenn der Wert true ist, ist die Bearbeitung der Form verboten. Standardmäßig ist der Wert false, die Form kann in Excel bearbeitet werden.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Setzt einen Wert, der angibt, ob die Bearbeitung der Form in Excel verboten ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Wenn der Wert true ist, ist die Bearbeitung der Form verboten. Standardmäßig ist der Wert false, die Form kann in Excel bearbeitet werden. |
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

