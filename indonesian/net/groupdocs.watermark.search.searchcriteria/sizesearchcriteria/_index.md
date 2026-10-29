---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili kriteria yang memungkinkan penyaringan berdasarkan ukuran watermark."
type: docs
weight: 2730
url: /id/net/groupdocs.watermark.search.searchcriteria/sizesearchcriteria/
---
## SizeSearchCriteria class

Mewakili kriteria yang memungkinkan penyaringan berdasarkan ukuran watermark.

```csharp
public class SizeSearchCriteria : SearchCriteria
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SizeSearchCriteria](sizesearchcriteria)(Dimension, double, double) | Menginisialisasi instance baru dari kelas [`SizeSearchCriteria`](../sizesearchcriteria) dengan dimensi yang ditentukan, nilai awal, dan nilai akhir. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Dimension](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/dimension) { get; } | Mendapatkan dimensi watermark untuk pencarian. |
| [Maximum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/maximum) { get; } | Mendapatkan nilai akhir. |
| [Minimum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/minimum) { get; } | Mendapatkan nilai awal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Menggabungkan [`SearchCriteria`](../searchcriteria) ini dengan kriteria lain menggunakan operator logika AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Membalikkan [`SearchCriteria`](../searchcriteria) ini. |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Menggabungkan [`SearchCriteria`](../searchcriteria) ini dengan kriteria lain menggunakan operator logika OR. |

### Catatan

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Contoh

Temukan dan hapus watermark menggunakan kriteria pencarian.

```csharp
using (Watermarker watermarker = new Watermarker(@"C:\test.some_ext"))
{
    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
    TextSearchCriteria textCriteria = new TextSearchCriteria(new Regex("^Test watermark$"));
    PossibleWatermarkCollection watermarks = watermarker.Search(textCriteria.And(widthRange.Or(rotateAngle)));
    watermarks.Clear();
    watermarker.Save();
}
```

### Lihat Juga

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
