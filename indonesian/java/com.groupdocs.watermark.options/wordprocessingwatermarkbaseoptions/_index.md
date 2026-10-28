---
title: "WordProcessingWatermarkBaseOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Kelas dasar untuk opsi penambahan watermark ke dokumen Word."
type: docs
weight: 73
url: /id/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Kelas dasar untuk opsi penambahan watermark ke dokumen Word.

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
|  | [getName()](#getName--) | Mendapatkan nama shape. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Mengatur nama shape. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Mendapatkan teks deskriptif (alternatif) yang akan terkait dengan shape. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Mengatur teks deskriptif (alternatif) yang akan terkait dengan shape. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
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
int - Tipe kunci watermark `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

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
|  | value | int | Tipe kunci watermark `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
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

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama shape.


**Returns:**
java.lang.String - Nama shape.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mengatur nama shape.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Nama shape. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Mendapatkan teks deskriptif (alternatif) yang akan terkait dengan shape.


**Returns:**
java.lang.String - Teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Mengatur teks deskriptif (alternatif) yang akan terkait dengan shape.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk. |
|

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

