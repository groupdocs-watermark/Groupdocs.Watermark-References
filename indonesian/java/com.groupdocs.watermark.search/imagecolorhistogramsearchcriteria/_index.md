---
title: "ImageColorHistogramSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kriteria pencarian untuk menemukan gambar dalam konten."
type: docs
weight: 30
url: /id/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

Mewakili kriteria pencarian untuk menemukan gambar dalam konten.

<br />

*** ** * ** ***

Kriteria pencarian ini menggunakan histogram warna gambar untuk menghitung kemiripan gambar.

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Menginisialisasi instance baru dari kelas `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` dengan jalur file yang ditentukan. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Menginisialisasi instance baru dari kelas `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` dengan aliran yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | Mendapatkan jumlah bin yang akan digunakan untuk membangun histogram warna. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | Mengatur jumlah bin yang akan digunakan untuk membangun histogram warna. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Menginisialisasi instance baru dari kelas `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` dengan jalur file yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file untuk memuat gambar. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Menginisialisasi instance baru dari kelas `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` dengan aliran yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | java.io.InputStream | Aliran untuk memuat gambar. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Mendapatkan jumlah bin yang akan digunakan untuk membangun histogram warna.


**Returns:**
byte - Nilai default adalah 10.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Mengatur jumlah bin yang akan digunakan untuk membangun histogram warna.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | byte | Nilai default adalah 10. |
|

