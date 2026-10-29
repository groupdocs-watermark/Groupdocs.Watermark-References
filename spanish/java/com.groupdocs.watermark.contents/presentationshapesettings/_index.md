---
title: "PresentationShapeSettings"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa la configuración que se puede aplicar a una marca de agua de forma para un documento PowerPoint."
type: docs
weight: 95
url: /es/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

Representa la configuración que se puede aplicar a una marca de agua de forma para un documento PowerPoint.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | Inicializa una nueva instancia de la clase `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`. |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isLocked()](#isLocked--) | Obtiene un valor que indica si la edición de la forma en PowerPoint está prohibida. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Establece un valor que indica si la edición de la forma en PowerPoint está prohibida. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Obtiene un valor que indica si los caracteres de la marca de agua de texto están mezclados con caracteres ilegibles. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Establece un valor que indica si los caracteres de la marca de agua de texto están mezclados con caracteres ilegibles. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


Inicializa una nueva instancia de la clase `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtiene un valor que indica si la edición de la forma en PowerPoint está prohibida.


**Returns:**
boolean - `true` si la edición de la forma está prohibida, `false` si la forma puede ser editada en PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Establece un valor que indica si la edición de la forma en PowerPoint está prohibida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | `true` si la edición de la forma debe ser prohibida, `false` si la forma puede ser editada en PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Obtiene un valor que indica si los caracteres de la marca de agua de texto están mezclados con caracteres ilegibles.

Esta protección se aplica solo cuando `#isLocked().isLocked()` devuelve `true`.


**Returns:**
boolean - Un valor que indica si los caracteres de la marca de agua de texto se mezclan con caracteres ilegibles.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Establece un valor que indica si los caracteres de la marca de agua de texto están mezclados con caracteres ilegibles.

Esta protección se aplica solo cuando `#isLocked().isLocked()` devuelve `true`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Un valor que indica si los caracteres de la marca de agua de texto están mezclados con caracteres ilegibles. |
|

