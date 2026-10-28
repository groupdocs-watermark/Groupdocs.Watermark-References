---
title: "WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Classe de base pour les options d'ajout de filigrane à un document Word."
type: docs
weight: 73
url: /fr/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Classe de base pour les options d'ajout de filigrane à un document Word.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isLocked()](#isLocked--) | Obtient une valeur indiquant si la modification de la forme dans Word est interdite. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Définit une valeur indiquant si la modification de la forme dans Word est interdite. |
|
|  | [getLockType()](#getLockType--) | Obtient le type de verrouillage du filigrane. |
|
|  | [setLockType(int value)](#setLockType-int-) | Définit le type de verrouillage du filigrane. |
|
|  | [getPassword()](#getPassword--) | Obtient le mot de passe utilisé pour verrouiller le filigrane. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définit le mot de passe utilisé pour verrouiller le filigrane. |
|
|  | [getName()](#getName--) | Obtient le nom d'une forme. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Définit le nom d'une forme. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtient le texte descriptif (alternatif) qui sera associé à une forme. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Définit le texte descriptif (alternatif) qui sera associé à une forme. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtient une valeur indiquant si la modification de la forme dans Word est interdite.


**Returns:**
boolean - Si la valeur est  true , la modification de la forme sera interdite. Par défaut, la valeur est  false , la forme peut être modifiée dans Word.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Définit une valeur indiquant si la modification de la forme dans Word est interdite.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Si la valeur est  true , la modification de la forme sera interdite. Par défaut, la valeur est  false , la forme peut être modifiée dans Word. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Obtient le type de verrouillage du filigrane.


**Returns:**
int - Le type de verrouillage du filigrane `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Définit le type de verrouillage du filigrane.

La valeur `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` ne peut pas être utilisée avec
un objet de type `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | int | Le type de verrouillage du filigrane `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient le mot de passe utilisé pour verrouiller le filigrane.


**Returns:**
java.lang.String - Un mot de passe utilisé pour verrouiller le filigrane.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définit le mot de passe utilisé pour verrouiller le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Un mot de passe utilisé pour verrouiller le filigrane. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom d'une forme.


**Returns:**
java.lang.String - Le nom de la forme.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Définit le nom d'une forme.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nom de la forme. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtient le texte descriptif (alternatif) qui sera associé à une forme.


**Returns:**
java.lang.String - Le texte descriptif (alternatif) qui sera associé à une forme.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Définit le texte descriptif (alternatif) qui sera associé à une forme.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le texte descriptif (alternatif) qui sera associé à une forme. |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

