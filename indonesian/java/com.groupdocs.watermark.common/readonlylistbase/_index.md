---
title: "ReadOnlyListBase"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan kelas dasar abstrak untuk daftar hanya-baca yang bertipe kuat."
type: docs
weight: 16
url: /id/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Menyediakan kelas dasar abstrak untuk daftar hanya-baca yang bertipe kuat.


T
: Tipe elemen.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCount()](#getCount--) | Mendapatkan jumlah elemen yang terdapat dalam koleksi. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan dalam koleksi. |
|
|  | [contains(T item)](#contains-T-) | Menentukan apakah koleksi berisi item tertentu. |
|
|  | [indexOf(T item)](#indexOf-T-) | Menentukan indeks dari item tertentu dalam koleksi. |
|
|  | [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


Mendapatkan jumlah elemen yang terdapat dalam koleksi.


**Returns:**
int - Jumlah elemen yang terdapat dalam koleksi.

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


Mendapatkan elemen pada indeks yang ditentukan dalam koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | indeks | int | Indeks berbasis nol dari elemen yang akan diambil. Nilai: Elemen pada indeks yang ditentukan. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Menentukan apakah koleksi berisi item tertentu.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | item | T | Item yang akan dicari dalam koleksi. |
|

**Returns:**
boolean - True jika item ditemukan dalam koleksi; jika tidak, false.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Menentukan indeks dari item tertentu dalam koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | item | T | Item yang akan dicari dalam koleksi. |
|

**Returns:**
int - Indeks dari  item  jika ditemukan dalam koleksi; jika tidak, -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.


**Returns:**
java.util.Iterator<T> - Sebuah objek  IEnumerator{T}  yang dapat digunakan untuk mengiterasi koleksi.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | T |  |

