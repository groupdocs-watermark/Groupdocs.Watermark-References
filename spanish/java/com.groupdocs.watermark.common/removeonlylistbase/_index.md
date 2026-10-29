---
title: "RemoveOnlyListBase"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona la clase base abstracta para una lista de solo eliminación fuertemente tipada."
type: docs
weight: 17
url: /es/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Proporciona la clase base abstracta para una lista de solo eliminación fuertemente tipada.


T
: El tipo del elemento.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura. |
|
|  | [clear()](#clear--) | Elimina todos los elementos de la colección. |
|
|  | [remove(T item)](#remove-T-) | Elimina la primera aparición de un objeto específico de la colección. |
|
|  | [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Obtiene un valor que indica si la colección es de solo lectura.


**Returns:**
boolean - Devuelve true si la colección es de solo lectura; de lo contrario, false.

### clear() {#clear--}
```
public final void clear()
```


Elimina todos los elementos de la colección.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Elimina la primera aparición de un objeto específico de la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | elemento | T | El elemento a eliminar de la colección. |
|

**Returns:**
boolean - True si el elemento se eliminó correctamente; de lo contrario false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina el elemento en el índice especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | índice | int | El índice basado en cero del elemento a eliminar. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elemento | T |  |

