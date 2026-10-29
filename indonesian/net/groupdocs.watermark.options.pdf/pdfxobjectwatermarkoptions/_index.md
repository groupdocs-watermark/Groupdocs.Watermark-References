---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark XObject ke dokumen pdf."
type: docs
weight: 1990
url: /id/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

Mewakili opsi penambahan watermark saat menambahkan watermark XObject ke dokumen pdf.

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | Menginisialisasi instance baru dari kelas [`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | Mendapatkan atau mengatur indeks halaman tempat menambahkan watermark. |

### Catatan

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Contoh

Tambahkan watermark ke halaman tertentu dari dokumen pdf.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Lihat Juga

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
