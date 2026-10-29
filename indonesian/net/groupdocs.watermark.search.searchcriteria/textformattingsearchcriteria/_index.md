---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili kriteria yang memungkinkan penyaringan berdasarkan format teks."
type: docs
weight: 2740
url: /id/net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
---
## TextFormattingSearchCriteria class

Mewakili kriteria yang memungkinkan penyaringan berdasarkan format teks.

```csharp
public class TextFormattingSearchCriteria : SearchCriteria
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextFormattingSearchCriteria](textformattingsearchcriteria)() | Menginisialisasi instance baru dari kelas [`TextFormattingSearchCriteria`](../textformattingsearchcriteria). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/backgroundcolorrange) { get; set; } | Mendapatkan atau mengatur rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar belakang teks. |
| [FontBold](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontbold) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah font yang digunakan dalam format teks watermark tebal. |
| [FontItalic](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontitalic) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah font yang digunakan dalam format teks watermark miring. |
| [FontName](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontname) { get; set; } | Mendapatkan atau mengatur nama font yang digunakan dalam kemungkinan format teks watermark. |
| [FontStrikeout](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontstrikeout) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah font yang digunakan dalam format teks watermark dicoret. |
| [FontUnderline](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontunderline) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah font yang digunakan dalam format teks watermark digarisbawahi. |
| [ForegroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foregroundcolorrange) { get; set; } | Mendapatkan atau mengatur rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar depan teks. |
| [MaxFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/maxfontsize) { get; set; } | Mendapatkan atau mengatur nilai akhir ukuran font. |
| [MinFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/minfontsize) { get; set; } | Mendapatkan atau mengatur nilai awal ukuran font. |

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

Hapus watermark yang mungkin dengan format teks tertentu (tanpa memandang jenis dokumen).

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.doc"))
{
    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
    criteria.ForegroundColorRange = new ColorRange();
    criteria.ForegroundColorRange.MinHue = -5;
    criteria.ForegroundColorRange.MaxHue = 10;
    criteria.ForegroundColorRange.MinBrightness = 0.01f;
    criteria.ForegroundColorRange.MaxBrightness = 0.99f;
    criteria.BackgroundColorRange = new ColorRange();
    criteria.BackgroundColorRange.IsEmpty = true;
    criteria.FontName = "Arial";
    criteria.MinFontSize = 19;
    criteria.MaxFontSize = 42;
    criteria.FontBold = true;

    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    watermarks.Clear();
    watermarker.Save();
}
```

### Lihat Juga

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
