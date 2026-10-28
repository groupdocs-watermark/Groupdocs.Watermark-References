---
title: "PresentationShapeSettings"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le impostazioni che possono essere applicate a una filigrana di forma per un documento PowerPoint."
type: docs
weight: 95
url: /it/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

Rappresenta le impostazioni che possono essere applicate a una filigrana di forma per un documento PowerPoint.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | Inizializza una nuova istanza della classe `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isLocked()](#isLocked--) | Restituisce un valore che indica se la modifica della forma in PowerPoint è vietata. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Imposta un valore che indica se la modifica della forma in PowerPoint è vietata. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Restituisce un valore che indica se i caratteri del watermark di testo sono mescolati con caratteri illeggibili. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Imposta un valore che indica se i caratteri del watermark di testo sono mescolati con caratteri illeggibili. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


Inizializza una nuova istanza della classe `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Restituisce un valore che indica se la modifica della forma in PowerPoint è vietata.


**Returns:**
boolean - `true` se la modifica della forma è vietata, `false` se la forma può essere modificata in PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Imposta un valore che indica se la modifica della forma in PowerPoint è vietata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | `true` se la modifica della forma dovrebbe essere vietata, `false` se la forma può essere modificata in PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Restituisce un valore che indica se i caratteri del watermark di testo sono mescolati con caratteri illeggibili.

Questa protezione si applica solo quando `#isLocked().isLocked()` restituisce `true`.


**Returns:**
boolean - Un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Imposta un valore che indica se i caratteri del watermark di testo sono mescolati con caratteri illeggibili.

Questa protezione si applica solo quando `#isLocked().isLocked()` restituisce `true`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili. |
|

