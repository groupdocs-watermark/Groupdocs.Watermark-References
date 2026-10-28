---
title: "PresentationShapeSettings"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Einstellungen dar, die auf ein Form-Wasserzeichen für ein PowerPoint-Dokument angewendet werden können."
type: docs
weight: 95
url: /de/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

Stellt Einstellungen dar, die auf ein Form-Wasserzeichen für ein PowerPoint-Dokument angewendet werden können.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | Initialisiert eine neue Instanz der Klasse `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`. |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isLocked()](#isLocked--) | Gibt einen Wert zurück, der angibt, ob das Bearbeiten der Form in PowerPoint verboten ist. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Setzt einen Wert, der angibt, ob das Bearbeiten der Form in PowerPoint verboten ist. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Liefert einen Wert, der angibt, ob die Textwasserzeichen‑Zeichen mit unlesbaren Zeichen gemischt sind. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Setzt einen Wert, der angibt, ob die Textwasserzeichen‑Zeichen mit unlesbaren Zeichen gemischt sind. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


Initialisiert eine neue Instanz der Klasse `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Gibt einen Wert zurück, der angibt, ob das Bearbeiten der Form in PowerPoint verboten ist.


**Returns:**
boolean - `true` wenn die Formbearbeitung verboten ist, `false` wenn die Form in PowerPoint bearbeitet werden kann.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Setzt einen Wert, der angibt, ob das Bearbeiten der Form in PowerPoint verboten ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | `true` wenn die Formbearbeitung verboten sein sollte, `false` wenn die Form in PowerPoint bearbeitet werden kann. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Liefert einen Wert, der angibt, ob die Textwasserzeichen‑Zeichen mit unlesbaren Zeichen gemischt sind.

Dieser Schutz gilt nur, wenn `#isLocked().isLocked()` `true` zurückgibt.


**Returns:**
boolesch – Ein Wert, der angibt, ob die Zeichen des Textwasserzeichens mit unlesbaren Zeichen gemischt werden.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Setzt einen Wert, der angibt, ob die Textwasserzeichen‑Zeichen mit unlesbaren Zeichen gemischt sind.

Dieser Schutz gilt nur, wenn `#isLocked().isLocked()` `true` zurückgibt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Ein Wert, der angibt, ob die Zeichen des Textwasserzeichens mit unlesbaren Zeichen gemischt sind. |
|

