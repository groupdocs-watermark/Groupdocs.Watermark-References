---
title: "PresentationShapeSettings"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les paramètres pouvant être appliqués à un filigrane de forme pour un document PowerPoint."
type: docs
weight: 95
url: /fr/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

Représente les paramètres pouvant être appliqués à un filigrane de forme pour un document PowerPoint.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | Initialise une nouvelle instance de la classe `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`. |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isLocked()](#isLocked--) | Obtient une valeur indiquant si la modification de la forme dans PowerPoint est interdite. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Définit une valeur indiquant si la modification de la forme dans PowerPoint est interdite. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Obtient une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Définit une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


Initialise une nouvelle instance de la classe `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtient une valeur indiquant si la modification de la forme dans PowerPoint est interdite.


**Returns:**
booléen - `true` si la modification de la forme est interdite, `false` si la forme peut être modifiée dans PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Définit une valeur indiquant si la modification de la forme dans PowerPoint est interdite.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | `true` si la modification de la forme doit être interdite, `false` si la forme peut être modifiée dans PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Obtient une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles.

Cette protection s'applique uniquement lorsque la méthode `#isLocked().isLocked()` renvoie `true`.


**Returns:**
booléen - Une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Définit une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles.

Cette protection s'applique uniquement lorsque la méthode `#isLocked().isLocked()` renvoie `true`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles. |
|

