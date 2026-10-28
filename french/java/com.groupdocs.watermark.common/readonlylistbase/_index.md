---
title: "ReadOnlyListBase"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit la classe de base abstraite pour une liste en lecture seule fortement typée."
type: docs
weight: 16
url: /fr/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Fournit la classe de base abstraite pour une liste en lecture seule fortement typée.


T
: Le type de l'élément.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCount()](#getCount--) | Obtient le nombre d'éléments contenus dans la collection. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié dans la collection. |
|
|  | [contains(T item)](#contains-T-) | Détermine si la collection contient un élément spécifique. |
|
|  | [indexOf(T item)](#indexOf-T-) | Détermine l'index d'un élément spécifique dans la collection. |
|
|  | [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt une collection. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


Obtient le nombre d'éléments contenus dans la collection.


**Returns:**
int - Le nombre d'éléments contenus dans la collection.

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


Obtient l'élément à l'index spécifié dans la collection.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | indice | int | L'index basé sur zéro de l'élément à obtenir. Valeur : L'élément à l'index spécifié. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Détermine si la collection contient un élément spécifique.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | élément | T | L'élément à localiser dans la collection. |
|

**Returns:**
boolean - Vrai si l'élément est trouvé dans la collection ; sinon, faux.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Détermine l'index d'un élément spécifique dans la collection.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | élément | T | L'élément à localiser dans la collection. |
|

**Returns:**
int - L'index de l'élément s'il est trouvé dans la collection ; sinon, -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Renvoie un énumérateur qui parcourt une collection.


**Returns:**
java.util.Iterator<T> - Un objet IEnumerator{T} qui peut être utilisé pour parcourir la collection.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| élément | T |  |

