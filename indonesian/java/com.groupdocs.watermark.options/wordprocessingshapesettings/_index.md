---
title: "WordProcessingShapeSettings"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili pengaturan yang dapat diterapkan pada watermark bentuk untuk dokumen Word."
type: docs
weight: 71
url: /id/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Mewakili pengaturan yang dapat diterapkan pada watermark bentuk untuk dokumen Word.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Menginisialisasi instance baru dari kelas `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isLocked()](#isLocked--) | Mendapatkan nilai yang menunjukkan apakah penyuntingan bentuk di Word dilarang. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Mengatur nilai yang menunjukkan apakah penyuntingan bentuk di Word dilarang. |
|
|  | [getLockType()](#getLockType--) | Mendapatkan tipe kunci watermark. |
|
|  | [setLockType(int value)](#setLockType-int-) | Mengatur tipe kunci watermark. |
|
|  | [getPassword()](#getPassword--) | Mendapatkan kata sandi yang digunakan untuk mengunci watermark. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mengatur kata sandi yang digunakan untuk mengunci watermark. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Mendapatkan nomor halaman untuk menambahkan watermark. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Mengatur nomor halaman untuk menambahkan watermark. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Menginisialisasi instance baru dari kelas `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`.


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Mendapatkan nilai yang menunjukkan apakah penyuntingan bentuk di Word dilarang.


**Returns:**
boolean - Jika nilai adalah  true , penyuntingan bentuk akan dilarang. Secara default, nilai adalah  false , bentuk dapat disunting di Word.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Mengatur nilai yang menunjukkan apakah penyuntingan bentuk di Word dilarang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Jika nilai adalah true, penyuntingan bentuk akan dilarang. Secara default, nilai adalah false, bentuk dapat disunting di Word. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Mendapatkan tipe kunci watermark.


**Returns:**
int - Tipe kunci watermark dari `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Mengatur tipe kunci watermark.

Nilai `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` tidak dapat digunakan dengan
sebuah objek bertipe `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Tipe kunci watermark dari `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mendapatkan kata sandi yang digunakan untuk mengunci watermark.


**Returns:**
java.lang.String - Kata sandi yang digunakan untuk mengunci watermark.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mengatur kata sandi yang digunakan untuk mengunci watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Kata sandi yang digunakan untuk mengunci watermark. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Mendapatkan nomor halaman untuk menambahkan watermark.


**Returns:**
int[] - Nomor halaman untuk menambahkan watermark.

<br />

*** ** * ** ***

Semua angka harus lebih besar atau sama dengan 1. Properti ini hanya digunakan saat menambahkan watermark ke dokumen. Jika nilai ini adalah null, watermark ditambahkan ke semua halaman.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Mengatur nomor halaman untuk menambahkan watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int[] | Nomor halaman untuk menambahkan watermark. |

<br />

*** ** * ** ***

Semua angka harus lebih besar atau sama dengan 1. Properti ini hanya digunakan saat menambahkan watermark ke dokumen. Jika nilai ini adalah null, watermark ditambahkan ke semua halaman.

<br />

|

