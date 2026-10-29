---
title: "PdfPage"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili halaman dokumen pdf."
type: docs
weight: 730
url: /id/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

Mewakili halaman dokumen pdf.

```csharp
public class PdfPage : ContentPart
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | Mendapatkan koleksi semua anotasi dari [`PdfPage`](../pdfpage) ini. |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | Mendapatkan koleksi semua artefak dari [`PdfPage`](../pdfpage) ini. |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | Mendapatkan tinggi dari [`PdfPage`](../pdfpage) ini dalam poin. |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | Mendapatkan lebar dari [`PdfPage`](../pdfpage) ini dalam poin. |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | Mendapatkan koleksi semua XObject dari [`PdfPage`](../pdfpage) ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Menemukan semua gambar dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | Mengonversi konten halaman menjadi gambar. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Menemukan semua watermark yang mungkin dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Lihat Juga

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
