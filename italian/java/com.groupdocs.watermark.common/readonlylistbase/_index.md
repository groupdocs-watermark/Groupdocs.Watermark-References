---
title: "ReadOnlyListBase"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce la classe base astratta per un elenco di sola lettura tipizzato in modo rigoroso."
type: docs
weight: 16
url: /it/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Fornisce la classe base astratta per un elenco di sola lettura tipizzato in modo rigoroso.


T
: Il tipo dell'elemento.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCount()](#getCount--) | Ottiene il numero di elementi contenuti nella collezione. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato nella collezione. |
|
|  | [contains(T item)](#contains-T-) | Determina se la collezione contiene un elemento specifico. |
|
|  | [indexOf(T item)](#indexOf-T-) | Determina l'indice di un elemento specifico nella collezione. |
|
|  | [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso una collezione. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


Ottiene il numero di elementi contenuti nella collezione.


**Returns:**
int - Il numero di elementi contenuti nella collezione.

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


Ottiene l'elemento all'indice specificato nella collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | indice | int | L'indice basato su zero dell'elemento da ottenere. Valore: L'elemento all'indice specificato. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Determina se la collezione contiene un elemento specifico.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | elemento | T | L'elemento da individuare nella collezione. |
|

**Returns:**
boolean - True se l'elemento è trovato nella collezione; altrimenti, false.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Determina l'indice di un elemento specifico nella collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | elemento | T | L'elemento da individuare nella collezione. |
|

**Returns:**
int - L'indice dell'elemento se trovato nella collezione; altrimenti, -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Restituisce un enumeratore che itera attraverso una collezione.


**Returns:**
java.util.Iterator<T> - Un oggetto IEnumerator{T} che può essere usato per iterare attraverso la collezione.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elemento | T |  |

