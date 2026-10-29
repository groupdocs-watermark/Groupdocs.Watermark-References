---
title: "WordProcessingWatermarkBaseOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Clase base para opciones de adición de marca de agua a un documento Word."
type: docs
weight: 73
url: /es/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Clase base para opciones de adición de marca de agua a un documento Word.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [isLocked()](#isLocked--) | Obtiene un valor que indica si la edición de la forma en Word está prohibida. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Establece un valor que indica si la edición de la forma en Word está prohibida. |
|
|  | [getLockType()](#getLockType--) | Obtiene el tipo de bloqueo de la marca de agua. |
|
|  | [setLockType(int value)](#setLockType-int-) | Establece el tipo de bloqueo de la marca de agua. |
|
|  | [getPassword()](#getPassword--) | Obtiene una contraseña utilizada para bloquear la marca de agua. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establece una contraseña utilizada para bloquear la marca de agua. |
|
|  | [getName()](#getName--) | Obtiene el nombre de una forma. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Establece el nombre de una forma. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtiene el texto descriptivo (alternativo) que se asociará a una forma. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Establece el texto descriptivo (alternativo) que se asociará a una forma. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtiene un valor que indica si la edición de la forma en Word está prohibida.


**Returns:**
boolean - Si el valor es  true , la edición de la forma será prohibida. Por defecto, el valor es  false , la forma puede ser editada en Word.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Establece un valor que indica si la edición de la forma en Word está prohibida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Si el valor es  true , la edición de formas estará prohibida. Por defecto, el valor es  false , la forma puede editarse en Word. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Obtiene el tipo de bloqueo de la marca de agua.


**Returns:**
int - El tipo de bloqueo de la marca de agua `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Establece el tipo de bloqueo de la marca de agua.

El valor `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` no puede usarse con
un objeto del tipo `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | int | El tipo de bloqueo de la marca de agua `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtiene una contraseña utilizada para bloquear la marca de agua.


**Returns:**
java.lang.String - Una contraseña utilizada para bloquear la marca de agua.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Establece una contraseña utilizada para bloquear la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | Una contraseña utilizada para bloquear la marca de agua. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de una forma.


**Returns:**
java.lang.String - El nombre de la forma.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Establece el nombre de una forma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nombre de la forma. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtiene el texto descriptivo (alternativo) que se asociará a una forma.


**Returns:**
java.lang.String - El texto descriptivo (alternativo) que se asociará con una forma.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Establece el texto descriptivo (alternativo) que se asociará a una forma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El texto descriptivo (alternativo) que se asociará con una forma. |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

