---
title: "RemoveOnlyListBase"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit la classe de base abstraite pour une liste en suppression uniquement fortement typée."
type: docs
weight: 17
url: /fr/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Fournit la classe de base abstraite pour une liste en suppression uniquement fortement typée.


T
: Le type de l'élément.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. |
|
|  | [clear()](#clear--) | Supprime tous les éléments de la collection. |
|
|  | [remove(T item)](#remove-T-) | Supprime la première occurrence d'un objet spécifique de la collection. |
|
|  | [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Obtient une valeur indiquant si la collection est en lecture seule.


**Returns:**
boolean - Renvoie true si la collection est en lecture seule ; sinon, false.

### clear() {#clear--}
```
public final void clear()
```


Supprime tous les éléments de la collection.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Supprime la première occurrence d'un objet spécifique de la collection.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | élément | T | L'élément à supprimer de la collection. |
|

**Returns:**
boolean - True si l'élément a été supprimé avec succès ; sinon false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Supprime l'élément à l'index spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | indice | int | L'index basé sur zéro de l'élément à supprimer. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| élément | T |  |

