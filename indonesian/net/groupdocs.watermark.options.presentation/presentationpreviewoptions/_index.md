---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran bagi pembuatan pratinjau dokumen Presentation."
type: docs
weight: 2030
url: /id/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/
---
## PresentationPreviewOptions class

Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran bagi pembuatan pratinjau dokumen Presentation.

```csharp
public class PresentationPreviewOptions : PreviewOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor)(CreatePageStream) | Menginisialisasi instance baru dari kelas [`PresentationPreviewOptions`](../presentationpreviewoptions) yang menyebabkan aliran output ditutup. |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Menginisialisasi instance baru dari kelas [`PresentationPreviewOptions`](../presentationpreviewoptions) yang menyebabkan aliran output dikembalikan ke klien untuk penggunaan lebih lanjut. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Mendapatkan atau mengatur instance delegasi pembuatan aliran halaman. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Mendapatkan atau mengatur tinggi pratinjau halaman. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Mendapatkan atau mengatur array nomor halaman untuk menghasilkan pratinjau. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Mendapatkan atau mengatur format gambar pratinjau. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Mendapatkan atau mengatur instance delegasi penyelesaian pratinjau halaman. |
| [Resolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/resolution) { get; set; } | Mendapatkan atau mengatur resolusi untuk gambar yang dihasilkan, dalam titik per inci. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Mendapatkan atau mengatur lebar pratinjau halaman. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/defaultresolution) | Resolusi default dalam titik per inci. |

### Lihat Juga

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
