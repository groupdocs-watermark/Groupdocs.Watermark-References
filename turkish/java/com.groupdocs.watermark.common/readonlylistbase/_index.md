---
title: "ReadOnlyListBase"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Güçlü tipli yalnızca okunabilir bir liste için soyut temel sınıfı sağlar."
type: docs
weight: 16
url: /tr/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Güçlü tipli yalnızca okunabilir bir liste için soyut temel sınıfı sağlar.


T
: öğenin türü.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCount()](#getCount--) | Koleksiyonda bulunan öğelerin sayısını alır. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | Koleksiyonda belirtilen indeksteki öğeyi alır. |
|
|  | [contains(T item)](#contains-T-) | Koleksiyonun belirli bir öğeyi içerip içermediğini belirler. |
|
|  | [indexOf(T item)](#indexOf-T-) | Koleksiyondaki belirli bir öğenin indeksini belirler. |
|
|  | [iterator()](#iterator--) | Bir koleksiyon üzerinde yineleme yapan bir enumerator döndürür. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


Koleksiyonda bulunan öğelerin sayısını alır.


**Returns:**
int - Koleksiyonda bulunan öğelerin sayısı.

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


Koleksiyonda belirtilen indeksteki öğeyi alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | index | int | Alınacak öğenin sıfır tabanlı indeksi. Değer: Belirtilen indeksteki öğe. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Koleksiyonun belirli bir öğeyi içerip içermediğini belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | item | T | Koleksiyonda bulunacak öğe. |
|

**Returns:**
boolean - Öğenin koleksiyonda bulunması durumunda true; aksi takdirde false.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Koleksiyondaki belirli bir öğenin indeksini belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | item | T | Koleksiyonda bulunacak öğe. |
|

**Returns:**
int - Öğenin koleksiyonda bulunması durumunda indeksi; aksi takdirde -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Bir koleksiyon üzerinde yineleme yapan bir enumerator döndürür.


**Returns:**
java.util.Iterator<T> - Koleksiyon üzerinde yineleme yapmak için kullanılabilecek bir IEnumerator{T} nesnesi.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | T |  |

