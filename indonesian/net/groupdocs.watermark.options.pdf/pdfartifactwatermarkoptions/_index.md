---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark artefak ke dokumen pdf."
type: docs
weight: 1940
url: /id/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

Mewakili opsi penambahan watermark saat menambahkan watermark artefak ke dokumen pdf.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | Menginisialisasi instance baru dari kelas [`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | Mendapatkan atau mengatur indeks halaman tempat menambahkan watermark. |

### Catatan

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Contoh

Tambahkan watermark artefak gambar ke dokumen PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### Lihat Juga

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
