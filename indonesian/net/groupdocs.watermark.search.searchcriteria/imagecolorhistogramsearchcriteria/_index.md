---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili kriteria pencarian untuk menemukan gambar dalam konten."
type: docs
weight: 2620
url: /id/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

Mewakili kriteria pencarian untuk menemukan gambar dalam konten.

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | Menginisialisasi instance baru dari kelas [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) dengan aliran yang ditentukan. |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | Menginisialisasi instance baru dari kelas [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) dengan jalur file yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | Mendapatkan atau mengatur jumlah bin yang akan digunakan untuk membangun histogram warna. |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Mendapatkan atau mengatur perbedaan maksimum yang diizinkan antara gambar. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Mendapatkan atau mengatur daftar nomor halaman tertentu |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Menggabungkan [`SearchCriteria`](../searchcriteria) ini dengan kriteria lain menggunakan operator logika AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Membalikkan [`SearchCriteria`](../searchcriteria) ini. |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Menggabungkan [`SearchCriteria`](../searchcriteria) ini dengan kriteria lain menggunakan operator logika OR. |

### Catatan

Kriteria pencarian ini menggunakan histogram warna gambar untuk menghitung kemiripan gambar.

### Lihat Juga

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
