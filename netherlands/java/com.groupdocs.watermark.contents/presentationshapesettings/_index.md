---
title: "PresentationShapeSettings"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt instellingen voor die op een vormwatermerk voor een PowerPoint-document kunnen worden toegepast."
type: docs
weight: 95
url: /nl/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

Stelt instellingen voor die op een vormwatermerk voor een PowerPoint-document kunnen worden toegepast.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | Initialiseert een nieuw exemplaar van de `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` klasse. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isLocked()](#isLocked--) | Haalt een waarde op die aangeeft of bewerken van de vorm in PowerPoint verboden is. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Stelt een waarde in die aangeeft of bewerken van de vorm in PowerPoint verboden is. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Haalt een waarde op die aangeeft of de tekens van de tekstwatermark gemengd zijn met onleesbare tekens. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Stelt een waarde in die aangeeft of de tekens van de tekstwatermark gemengd zijn met onleesbare tekens. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


Initialiseert een nieuw exemplaar van de `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` klasse.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Haalt een waarde op die aangeeft of bewerken van de vorm in PowerPoint verboden is.


**Returns:**
boolean - `true` als bewerken van vormen verboden is, `false` als de vorm bewerkt kan worden in PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Stelt een waarde in die aangeeft of bewerken van de vorm in PowerPoint verboden is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | `true` als bewerken van vormen verboden moet zijn, `false` als de vorm bewerkt kan worden in PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Haalt een waarde op die aangeeft of de tekens van de tekstwatermark gemengd zijn met onleesbare tekens.

Deze bescherming is alleen van toepassing wanneer de `#isLocked().isLocked()` `true` retourneert.


**Returns:**
boolean - Een waarde die aangeeft of de tekens van het tekstwatermerk gemengd zijn met onleesbare tekens.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Stelt een waarde in die aangeeft of de tekens van de tekstwatermark gemengd zijn met onleesbare tekens.

Deze bescherming is alleen van toepassing wanneer de `#isLocked().isLocked()` `true` retourneert.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | Een waarde die aangeeft of de tekstopwatermerktekens gemengd zijn met onleesbare tekens. |
|

