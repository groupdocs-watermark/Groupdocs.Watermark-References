---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark anotasi ke dokumen pdf."
type: docs
weight: 1930
url: /id/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

Mewakili opsi penambahan watermark saat menambahkan watermark anotasi ke dokumen pdf.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | Menginisialisasi instance baru dari kelas [`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | Mendapatkan atau mengatur indeks halaman tempat menambahkan watermark. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah anotasi akan dicetak, tetapi tidak ditampilkan dalam aplikasi penampil pdf. |

### Catatan

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Contoh

Tambahkan watermark anotasi gambar ke dokumen PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### Lihat Juga

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
