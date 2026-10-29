---
title: "ReadOnlyListBase"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona la clase base abstracta para una lista de solo lectura fuertemente tipada."
type: docs
weight: 16
url: /es/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Proporciona la clase base abstracta para una lista de solo lectura fuertemente tipada.


T
: El tipo del elemento.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCount()](#getCount--) | Obtiene el número de elementos contenidos en la colección. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado de la colección. |
|
|  | [contains(T item)](#contains-T-) | Determina si la colección contiene un elemento específico. |
|
|  | [indexOf(T item)](#indexOf-T-) | Determina el índice de un elemento específico en la colección. |
|
|  | [iterator()](#iterator--) | Devuelve un enumerador que recorre una colección. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


Obtiene el número de elementos contenidos en la colección.


**Returns:**
int - El número de elementos contenidos en la colección.

### getInnerList() {#getInnerList--}
```
public final System.Collections.Generic.List<T> getInnerList()
```


<br />



**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### get_Item(int index) {#get-Item-int-}
```
public T get_Item(int index)
```


Obtiene el elemento en el índice especificado de la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | índice | int | El índice basado en cero del elemento a obtener. Valor: El elemento en el índice especificado. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Determina si la colección contiene un elemento específico.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | elemento | T | El elemento a localizar en la colección. |
|

**Returns:**
boolean - Verdadero si el elemento se encuentra en la colección; de lo contrario, falso.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Determina el índice de un elemento específico en la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | elemento | T | El elemento a localizar en la colección. |
|

**Returns:**
int - El índice del elemento si se encuentra en la colección; de lo contrario, -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Devuelve un enumerador que recorre una colección.


**Returns:**
java.util.Iterator<T> - Un objeto IEnumerator{T} que puede usarse para iterar a través de la colección.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elemento | T |  |

