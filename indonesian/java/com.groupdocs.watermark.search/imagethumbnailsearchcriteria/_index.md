---
title: "ImageThumbnailSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kriteria pencarian untuk menemukan gambar dalam konten."
type: docs
weight: 33
url: /id/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

Mewakili kriteria pencarian untuk menemukan gambar dalam konten.

<br />

*** ** * ** ***

Kriteria pencarian ini menggunakan thumbnail gambar yang dibinarisasi untuk menghitung kemiripan gambar.

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Menginisialisasi instance baru dari kelas `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` dengan jalur file yang ditentukan. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Menginisialisasi instance baru dari kelas `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` dengan aliran yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | Mendapatkan ukuran thumbnail. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Mengatur ukuran thumbnail. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Menginisialisasi instance baru dari kelas `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` dengan jalur file yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file untuk memuat gambar. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Menginisialisasi instance baru dari kelas `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` dengan aliran yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | java.io.InputStream | Aliran untuk memuat gambar. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Mendapatkan ukuran thumbnail.


**Returns:**
byte - Secara default thumbnail 32X32 akan digunakan.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Mengatur ukuran thumbnail.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | byte | Secara default thumbnail 32X32 akan digunakan. |
|

