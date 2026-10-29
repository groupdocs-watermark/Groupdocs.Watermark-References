---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili kriteria yang memungkinkan penyaringan berdasarkan teks watermark."
type: docs
weight: 2750
url: /id/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

Mewakili kriteria yang memungkinkan penyaringan berdasarkan teks watermark.

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | Menginisialisasi instance baru dari kelas [`TextSearchCriteria`](../textsearchcriteria) dengan ekspresi reguler yang ditentukan. |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | Menginisialisasi instance baru dari kelas [`TextSearchCriteria`](../textsearchcriteria) dengan string pencarian. |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | Menginisialisasi instance baru dari kelas [`TextSearchCriteria`](../textsearchcriteria) dengan string pencarian dan bendera untuk perbandingan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Mendapatkan atau mengatur daftar nomor halaman tertentu |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | Mendapatkan pola pencarian. |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan bahwa karakter yang tidak dapat dibaca akan dilewati selama perbandingan string. |

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

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
