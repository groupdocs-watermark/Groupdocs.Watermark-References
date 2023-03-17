---
title: TextFormattingSearchCriteria
second_title: GroupDocs.Watermark untuk Referensi .NET API
description: Mewakili kriteria yang memungkinkan pemfilteran dengan pemformatan teks.
type: docs
weight: 2690
url: /id/net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
---
## TextFormattingSearchCriteria class

Mewakili kriteria yang memungkinkan pemfilteran dengan pemformatan teks.

```csharp
public class TextFormattingSearchCriteria : SearchCriteria
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [TextFormattingSearchCriteria](textformattingsearchcriteria)() | Menginisialisasi instance baru dari[`TextFormattingSearchCriteria`](../textformattingsearchcriteria) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BackgroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/backgroundcolorrange) { get; set; } | Mendapat atau menyetel rentang warna yang digunakan untuk memfilter tanda air berdasarkan warna latar belakang teks. |
| [FontBold](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontbold) { get; set; } | Mendapat atau menyetel nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark dicetak tebal. |
| [FontItalic](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontitalic) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark miring. |
| [FontName](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontname) { get; set; } | Mendapatkan atau menyetel nama font yang digunakan dalam kemungkinan pemformatan teks watermark. |
| [FontStrikeout](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontstrikeout) { get; set; } | Mendapat atau menyetel nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks tanda air dicoret. |
| [FontUnderline](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontunderline) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark bergaris bawah. |
| [ForegroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foregroundcolorrange) { get; set; } | Mendapat atau menyetel rentang warna yang digunakan untuk memfilter tanda air berdasarkan warna latar depan teks. |
| [MaxFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/maxfontsize) { get; set; } | Mendapat atau menetapkan nilai akhir dari ukuran font. |
| [MinFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/minfontsize) { get; set; } | Mendapat atau menetapkan nilai awal dari ukuran font. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Gabungkan ini[`SearchCriteria`](../searchcriteria) dengan kriteria lain menggunakan logika AND operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Meniadakan ini[`SearchCriteria`](../searchcriteria) . |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Gabungkan ini[`SearchCriteria`](../searchcriteria) dengan kriteria lain menggunakan logika OR operator. |

### Perkataan

**Belajarlah lagi:**

* [Mencari tanda air](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Contoh

Hapus kemungkinan tanda air dengan pemformatan teks tertentu (terlepas dari jenis dokumen).

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

### Lihat juga

* class [SearchCriteria](../searchcriteria)
* ruang nama [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* perakitan [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->