---
title: "ReadOnlyListBase"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt de abstracte basisklasse voor een sterk getypeerde alleen‑lezen‑lijst."
type: docs
weight: 16
url: /nl/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Biedt de abstracte basisklasse voor een sterk getypeerde alleen‑lezen‑lijst.


T
: Het type van het element.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCount()](#getCount--) | Haalt het aantal elementen op dat in de collectie is opgenomen. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index in de collectie. |
|
|  | [contains(T item)](#contains-T-) | Bepaalt of de collectie een specifiek item bevat. |
|
|  | [indexOf(T item)](#indexOf-T-) | Bepaalt de index van een specifiek item in de collectie. |
|
|  | [iterator()](#iterator--) | Retourneert een enumerator die door een collectie iterereert. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


Haalt het aantal elementen op dat in de collectie is opgenomen.


**Returns:**
int - Het aantal elementen dat in de collectie is opgenomen.

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


Haalt het element op op de opgegeven index in de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | index | int | De nulgebaseerde index van het op te halen element. Waarde: Het element op de opgegeven index. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Bepaalt of de collectie een specifiek item bevat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | item | T | Het item om in de collectie te vinden. |
|

**Returns:**
boolean - True als het item in de collectie wordt gevonden; anders false.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Bepaalt de index van een specifiek item in de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | item | T | Het item om in de collectie te vinden. |
|

**Returns:**
int - De index van het item als het in de collectie wordt gevonden; anders -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Retourneert een enumerator die door een collectie iterereert.


**Returns:**
java.util.Iterator<T> - Een IEnumerator{T} object dat kan worden gebruikt om door de collectie te itereren.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | T |  |

