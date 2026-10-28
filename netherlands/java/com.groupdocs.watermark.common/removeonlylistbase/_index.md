---
title: "RemoveOnlyListBase"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt de abstracte basisklasse voor een sterk getypeerde alleen‑verwijderen‑lijst."
type: docs
weight: 17
url: /nl/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Biedt de abstracte basisklasse voor een sterk getypeerde alleen‑verwijderen‑lijst.


T
: Het type van het element.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | Haalt een waarde op die aangeeft of de collectie alleen-lezen is. |
|
|  | [clear()](#clear--) | Verwijdert alle items uit de collectie. |
|
|  | [remove(T item)](#remove-T-) | Verwijdert de eerste instantie van een specifiek object uit de collectie. |
|
|  | [removeAt(int index)](#removeAt-int-) | Verwijdert het item op de opgegeven index. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Haalt een waarde op die aangeeft of de collectie alleen-lezen is.


**Returns:**
boolean - Retourneert true als de collectie alleen-lezen is; anders false.

### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle items uit de collectie.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Verwijdert de eerste instantie van een specifiek object uit de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | item | T | Het item dat uit de collectie moet worden verwijderd. |
|

**Returns:**
boolean - True als  item  succesvol is verwijderd; anders false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert het item op de opgegeven index.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | index | int | De nulgebaseerde index van het te verwijderen item. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | T |  |

