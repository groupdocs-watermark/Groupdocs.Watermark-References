---
title: "PresentationWatermarkableImage"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili gambar di dalam dokumen PowerPoint."
type: docs
weight: 1090
url: /id/net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/
---
## PresentationWatermarkableImage class

Mewakili gambar di dalam dokumen PowerPoint.

```csharp
public class PresentationWatermarkableImage : WatermarkableImage
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PresentationWatermarkableImage](presentationwatermarkableimage)(byte[]) | Menginisialisasi instance baru dari kelas [`PresentationWatermarkableImage`](../presentationwatermarkableimage) menggunakan data gambar yang ditentukan. |

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
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
