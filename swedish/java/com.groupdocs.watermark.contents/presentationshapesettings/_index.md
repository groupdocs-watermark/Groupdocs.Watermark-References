---
title: "PresentationShapeSettings"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar inställningar som kan tillämpas på en formvattenstämpel för ett PowerPoint-dokument."
type: docs
weight: 95
url: /sv/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

Representerar inställningar som kan tillämpas på en formvattenstämpel för ett PowerPoint-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | Initierar en ny instans av klassen `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isLocked()](#isLocked--) | Hämtar ett värde som indikerar om redigering av formen i PowerPoint är förbjuden. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Ställer in ett värde som indikerar om redigering av formen i PowerPoint är förbjuden. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Hämtar ett värde som indikerar om textvattenstämpelns tecken är blandade med oläsliga tecken. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Ställer in ett värde som indikerar om textvattenstämpelns tecken är blandade med oläsliga tecken. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


Initierar en ny instans av klassen `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Hämtar ett värde som indikerar om redigering av formen i PowerPoint är förbjuden.


**Returns:**
boolean - `true` om formredigering är förbjuden, `false` om formen kan redigeras i PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Ställer in ett värde som indikerar om redigering av formen i PowerPoint är förbjuden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | `true` om formredigering bör förbjudas, `false` om formen kan redigeras i PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Hämtar ett värde som indikerar om textvattenstämpelns tecken är blandade med oläsliga tecken.

Detta skydd gäller endast när `#isLocked().isLocked()` returnerar `true`.


**Returns:**
boolean – Ett värde som indikerar om tecken i textvattenstämpeln blandas med oläsliga tecken.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Ställer in ett värde som indikerar om textvattenstämpelns tecken är blandade med oläsliga tecken.

Detta skydd gäller endast när `#isLocked().isLocked()` returnerar `true`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Ett värde som indikerar om textvattenmärkestecknen är blandade med oläsliga tecken. |
|

