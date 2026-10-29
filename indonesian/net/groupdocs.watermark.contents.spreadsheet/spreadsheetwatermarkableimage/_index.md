---
title: "SpreadsheetWatermarkableImage"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili gambar di dalam dokumen Excel."
type: docs
weight: 1320
url: /id/net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/
---
## SpreadsheetWatermarkableImage class

Mewakili gambar di dalam dokumen Excel.

```csharp
public class SpreadsheetWatermarkableImage : WatermarkableImage
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SpreadsheetWatermarkableImage](spreadsheetwatermarkableimage)(byte[]) | Menginisialisasi sebuah instance baru dari kelas [`SpreadsheetWatermarkableImage`](../spreadsheetwatermarkableimage) menggunakan data gambar yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Mendapatkan tinggi dari [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) ini dalam piksel. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Mendapatkan lebar dari [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) ini dalam piksel. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Menambahkan watermark ke [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) ini. Metode ini mengasumsikan bahwa offset dan ukuran watermark diukur dalam piksel (jika telah ditetapkan). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Menemukan semua gambar dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Mendapatkan gambar sebagai array byte. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Menemukan semua watermark yang mungkin dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Lihat Juga

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
