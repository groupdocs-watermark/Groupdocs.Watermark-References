---
title: "RemoveOnlyListBase"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt die abstrakte Basisklasse für eine stark typisierte Nur-Entfernen-Liste bereit."
type: docs
weight: 17
url: /de/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Stellt die abstrakte Basisklasse für eine stark typisierte Nur-Entfernen-Liste bereit.


T
: Der Typ des Elements.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
|
|  | [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
|
|  | [remove(T item)](#remove-T-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
|
|  | [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist.


**Returns:**
boolean - Gibt true zurück, wenn die Sammlung schreibgeschützt ist; andernfalls false.

### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Elemente aus der Sammlung.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Element | T | Das zu entfernende Element aus der Sammlung. |
|

**Returns:**
boolean - True, wenn das Element erfolgreich entfernt wurde; andernfalls false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt das Element am angegebenen Index.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Index | int | Der nullbasierte Index des zu entfernenden Elements. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Element | T |  |

