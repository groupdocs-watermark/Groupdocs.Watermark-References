---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili kriteria pencarian untuk menemukan gambar dalam konten."
type: docs
weight: 2650
url: /id/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

Mewakili kriteria pencarian untuk menemukan gambar dalam konten.

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | Menginisialisasi instance baru dari kelas [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) dengan aliran yang ditentukan. |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | Menginisialisasi instance baru dari kelas [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) dengan jalur file yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Mendapatkan atau mengatur perbedaan maksimum yang diizinkan antara gambar. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Mendapatkan atau mengatur daftar nomor halaman tertentu |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | Mendapatkan atau mengatur ukuran thumbnail. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Menggabungkan [`SearchCriteria`](../searchcriteria) ini dengan kriteria lain menggunakan operator logika AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Membalikkan [`SearchCriteria`](../searchcriteria) ini. |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Menggabungkan [`SearchCriteria`](../searchcriteria) ini dengan kriteria lain menggunakan operator logika OR. |

### Catatan

Kriteria pencarian ini menggunakan thumbnail gambar terbinarisasi untuk menghitung kemiripan gambar.

### Lihat Juga

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
