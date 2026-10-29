---
title: "RemoveOnlyListBase"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Güçlü tipli yalnızca kaldırılabilir bir liste için soyut temel sınıfı sağlar."
type: docs
weight: 17
url: /tr/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Güçlü tipli yalnızca kaldırılabilir bir liste için soyut temel sınıfı sağlar.


T
: öğenin türü.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değer alır. |
|
|  | [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
|
|  | [remove(T item)](#remove-T-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
|
|  | [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki öğeyi kaldırır. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değer alır.


**Returns:**
boolean - Koleksiyon yalnızca okunur ise true döndürür; aksi takdirde false.

### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | item | T | Koleksiyondan kaldırılacak öğe. |
|

**Returns:**
boolean - Öğenin başarıyla kaldırıldıysa true; aksi takdirde false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Belirtilen indeksteki öğeyi kaldırır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | T |  |

