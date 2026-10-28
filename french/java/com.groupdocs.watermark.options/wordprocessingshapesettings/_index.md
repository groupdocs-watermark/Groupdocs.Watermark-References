---
title: "WordProcessingShapeSettings"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les paramètres qui peuvent être appliqués à un filigrane forme pour un document Word."
type: docs
weight: 71
url: /fr/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Représente les paramètres qui peuvent être appliqués à un filigrane forme pour un document Word.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Initialise une nouvelle instance de la classe `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`. |
|
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
|  | [getPageNumbers()](#getPageNumbers--) | Obtient les numéros de page où ajouter le filigrane. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Définit les numéros de page où ajouter le filigrane. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Initialise une nouvelle instance de la classe `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`.


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
int - Le type de verrouillage du filigrane de `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

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
|  | value | int | Le type de verrouillage du filigrane de `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
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

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtient les numéros de page où ajouter le filigrane.


**Returns:**
int[] - Les numéros de page où ajouter le filigrane.

<br />

*** ** * ** ***

Tous les nombres doivent être supérieurs ou égaux à 1. Cette propriété n'est utilisée que lors de l'ajout du filigrane à un document. Si cette valeur est  null , le filigrane est ajouté à toutes les pages.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Définit les numéros de page où ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int[] | Les numéros de page où ajouter le filigrane. |

<br />

*** ** * ** ***

Tous les nombres doivent être supérieurs ou égaux à 1. Cette propriété n'est utilisée que lors de l'ajout du filigrane à un document. Si cette valeur est  null , le filigrane est ajouté à toutes les pages.

<br />

|

