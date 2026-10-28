---
title: "RemoveOnlyListBase"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce la classe base astratta per un elenco di sola rimozione tipizzato in modo rigoroso."
type: docs
weight: 17
url: /it/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Fornisce la classe base astratta per un elenco di sola rimozione tipizzato in modo rigoroso.


T
: Il tipo dell'elemento.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | Ottiene un valore che indica se la collezione è di sola lettura. |
|
|  | [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
|
|  | [remove(T item)](#remove-T-) | Rimuove la prima occorrenza di un oggetto specifico dalla collezione. |
|
|  | [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Ottiene un valore che indica se la collezione è di sola lettura.


**Returns:**
boolean - Restituisce true se la collezione è di sola lettura; altrimenti, false.

### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti gli elementi dalla collezione.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Rimuove la prima occorrenza di un oggetto specifico dalla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | elemento | T | L'elemento da rimuovere dalla collezione. |
|

**Returns:**
boolean - True se l'elemento è stato rimosso con successo; altrimenti false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove l'elemento all'indice specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | indice | int | L'indice basato su zero dell'elemento da rimuovere. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elemento | T |  |

