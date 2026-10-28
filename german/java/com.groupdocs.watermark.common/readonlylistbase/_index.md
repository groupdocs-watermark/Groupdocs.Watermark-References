---
title: "ReadOnlyListBase"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt die abstrakte Basisklasse für eine stark typisierte schreibgeschützte Liste bereit."
type: docs
weight: 16
url: /de/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Stellt die abstrakte Basisklasse für eine stark typisierte schreibgeschützte Liste bereit.


T
: Der Typ des Elements.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getCount()](#getCount--) | Gibt die Anzahl der in der Sammlung enthaltenen Elemente zurück. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index in der Sammlung zurück. |
|
|  | [contains(T item)](#contains-T-) | Bestimmt, ob die Sammlung ein bestimmtes Element enthält. |
|
|  | [indexOf(T item)](#indexOf-T-) | Bestimmt den Index eines bestimmten Elements in der Sammlung. |
|
|  | [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch eine Sammlung iteriert. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


Gibt die Anzahl der in der Sammlung enthaltenen Elemente zurück.


**Returns:**
int - Die Anzahl der in der Sammlung enthaltenen Elemente.

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


Gibt das Element am angegebenen Index in der Sammlung zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Index | int | Der nullbasierte Index des abzurufenden Elements. Wert: Das Element am angegebenen Index. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Bestimmt, ob die Sammlung ein bestimmtes Element enthält.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Element | T | Das Element, das in der Sammlung gefunden werden soll. |
|

**Returns:**
boolean - Wahr, wenn das Element in der Sammlung gefunden wird; andernfalls falsch.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Bestimmt den Index eines bestimmten Elements in der Sammlung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Element | T | Das Element, das in der Sammlung gefunden werden soll. |
|

**Returns:**
int - Der Index des Elements, wenn es in der Sammlung gefunden wird; andernfalls -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Gibt einen Enumerator zurück, der durch eine Sammlung iteriert.


**Returns:**
java.util.Iterator<T> - Ein IEnumerator{T}-Objekt, das zum Durchlaufen der Sammlung verwendet werden kann.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Element | T |  |

