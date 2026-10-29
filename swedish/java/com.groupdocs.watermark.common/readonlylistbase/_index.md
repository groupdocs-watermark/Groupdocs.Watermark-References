---
title: "ReadOnlyListBase"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller den abstrakta basklassen för en starkt typad skrivskyddad lista."
type: docs
weight: 16
url: /sv/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Tillhandahåller den abstrakta basklassen för en starkt typad skrivskyddad lista.


T
: Typen av elementet.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCount()](#getCount--) | Hämtar antalet element som finns i samlingen. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet i samlingen. |
|
|  | [contains(T item)](#contains-T-) | Bestämmer om samlingen innehåller ett specifikt objekt. |
|
|  | [indexOf(T item)](#indexOf-T-) | Bestämmer indexet för ett specifikt objekt i samlingen. |
|
|  | [iterator()](#iterator--) | Returnerar en enumerator som itererar genom en samling. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


Hämtar antalet element som finns i samlingen.


**Returns:**
int - Antalet element som finns i samlingen.

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


Hämtar elementet på det angivna indexet i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | index | int | Det nollbaserade indexet för elementet som ska hämtas. Värde: Elementet på det angivna indexet. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Bestämmer om samlingen innehåller ett specifikt objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | objekt | T | Objektet att hitta i samlingen. |
|

**Returns:**
boolean - Sant om objektet finns i samlingen; annars falskt.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Bestämmer indexet för ett specifikt objekt i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | objekt | T | Objektet att hitta i samlingen. |
|

**Returns:**
int - Indexet för objektet om det finns i samlingen; annars -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Returnerar en enumerator som itererar genom en samling.


**Returns:**
java.util.Iterator<T> - Ett  IEnumerator{T}  objekt som kan användas för att iterera genom samlingen.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | T |  |

