---
title: "RemoveOnlyListBase"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan kelas dasar abstrak untuk daftar hanya-hapus yang bertipe kuat."
type: docs
weight: 17
url: /id/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Menyediakan kelas dasar abstrak untuk daftar hanya-hapus yang bertipe kuat.


T
: Tipe elemen.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only. |
|
|  | [clear()](#clear--) | Menghapus semua item dari koleksi. |
|
|  | [remove(T item)](#remove-T-) | Menghapus kemunculan pertama dari objek tertentu dari koleksi. |
|
|  | [removeAt(int index)](#removeAt-int-) | Menghapus item pada indeks yang ditentukan. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only.


**Returns:**
boolean - Mengembalikan true jika koleksi bersifat read-only; jika tidak, false.

### clear() {#clear--}
```
public final void clear()
```


Menghapus semua item dari koleksi.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Menghapus kemunculan pertama dari objek tertentu dari koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | item | T | Item yang akan dihapus dari koleksi. |
|

**Returns:**
boolean - True jika item berhasil dihapus; jika tidak false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus item pada indeks yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | indeks | int | Indeks berbasis nol dari item yang akan dihapus. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | T |  |

