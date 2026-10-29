---
title: "WordProcessingShapeSettings"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa configuraciones que pueden aplicarse a una marca de agua de forma para un documento de Word."
type: docs
weight: 71
url: /es/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Representa configuraciones que pueden aplicarse a una marca de agua de forma para un documento de Word.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Inicializa una nueva instancia de la clase `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`. |
|
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
|  | [getPageNumbers()](#getPageNumbers--) | Obtiene los números de página a los que se añadirá la marca de agua. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Establece los números de página a los que se añadirá la marca de agua. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Inicializa una nueva instancia de la clase `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`.


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
int - El tipo de bloqueo de marca de agua de `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

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
|  | value | int | El tipo de bloqueo de marca de agua de `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
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

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtiene los números de página a los que se añadirá la marca de agua.


**Returns:**
int[] - Los números de página a los que se añadirá la marca de agua.

<br />

*** ** * ** ***

Todos los números deben ser mayores o iguales a 1. Esta propiedad solo se usa al agregar la marca de agua a un documento. Si este valor es  null , la marca de agua se agrega a todas las páginas.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Establece los números de página a los que se añadirá la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int[] | Los números de página a los que se añadirá la marca de agua. |

<br />

*** ** * ** ***

Todos los números deben ser mayores o iguales a 1. Esta propiedad solo se usa al agregar la marca de agua a un documento. Si este valor es  null , la marca de agua se agrega a todas las páginas.

<br />

|

