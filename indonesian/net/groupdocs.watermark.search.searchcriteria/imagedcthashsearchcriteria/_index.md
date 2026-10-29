---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili kriteria pencarian untuk menemukan gambar dalam dokumen."
type: docs
weight: 2630
url: /id/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

Mewakili kriteria pencarian untuk menemukan gambar dalam dokumen.

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | Menginisialisasi instance baru dari kelas [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) dengan aliran yang ditentukan. |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | Menginisialisasi instance baru dari kelas [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) dengan jalur file yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Mendapatkan atau mengatur perbedaan maksimum yang diizinkan antara gambar. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Mendapatkan atau mengatur daftar nomor halaman tertentu |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Menggabungkan [`SearchCriteria`](../searchcriteria) ini dengan kriteria lain menggunakan operator logika AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Membalikkan [`SearchCriteria`](../searchcriteria) ini. |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Menggabungkan [`SearchCriteria`](../searchcriteria) ini dengan kriteria lain menggunakan operator logika OR. |

### Catatan

Kriteria pencarian ini menggunakan hash gambar perseptual berbasis DCT untuk menghitung kemiripan gambar. **Pelajari lebih lanjut:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Contoh

Cari gambar dalam file terlampir (pdf).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // Tentukan contoh gambar untuk membandingkan gambar dokumen dengan
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // Cari gambar serupa
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // Hapus atau modifikasi watermark gambar yang ditemukan
    // ...
}
```

### Lihat Juga

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
