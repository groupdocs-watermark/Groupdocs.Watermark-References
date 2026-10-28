---
title: "PagesSelector"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: 
type: docs
weight: 10
url: /id/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Mendapatkan daftar halaman berdasarkan pengaturan yang ditentukan. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Mendapatkan daftar halaman terpilih berdasarkan kriteria yang ditentukan. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Mendapatkan daftar halaman berdasarkan pengaturan yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | allPages | boolean | Apakah menyertakan semua halaman. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Konfigurasi pengaturan halaman. |
|
|  | totalPages | int | Jumlah total halaman. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | Indeks halaman spesifik (dimulai dari 0). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Daftar halaman berdasarkan pengaturan yang ditentukan.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Mendapatkan daftar halaman terpilih berdasarkan kriteria yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | allPages | boolean | Bendera yang menunjukkan apakah semua halaman harus disertakan. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Konfigurasi pengaturan untuk halaman. |
|
|  | totalPages | int | Jumlah total halaman dalam dokumen. |
|
|  | pageNumbers | int[] | Array nomor halaman spesifik yang akan disertakan. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Daftar nomor halaman terpilih yang diurutkan dan unik.

