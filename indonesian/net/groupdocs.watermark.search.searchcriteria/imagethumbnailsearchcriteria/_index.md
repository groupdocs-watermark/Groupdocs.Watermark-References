---
title: ImageThumbnailSearchCriteria
second_title: GroupDocs.Watermark untuk Referensi .NET API
description: Mewakili kriteria pencarian untuk menemukan gambar dalam suatu konten.
type: docs
weight: 2610
url: /id/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

Mewakili kriteria pencarian untuk menemukan gambar dalam suatu konten.

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | Menginisialisasi instance baru dari[`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) kelas dengan aliran tertentu. |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | Menginisialisasi instance baru dari[`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) kelas dengan jalur file tertentu. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Mendapat atau menyetel perbedaan maksimum yang diizinkan di antara gambar. |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | Mendapat atau menyetel ukuran thumbnail. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Gabungkan ini[`SearchCriteria`](../searchcriteria) dengan kriteria lain menggunakan logika AND operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Meniadakan ini[`SearchCriteria`](../searchcriteria) . |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Gabungkan ini[`SearchCriteria`](../searchcriteria) dengan kriteria lain menggunakan logika OR operator. |

### Perkataan

Kriteria pencarian ini menggunakan thumbnail gambar biner untuk menghitung kesamaan gambar.

### Lihat juga

* class [ImageSearchCriteria](../imagesearchcriteria)
* ruang nama [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* perakitan [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->