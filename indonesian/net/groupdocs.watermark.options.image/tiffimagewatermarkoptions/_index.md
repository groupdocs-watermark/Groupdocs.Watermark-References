---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark ke gambar TIFF."
type: docs
weight: 1900
url: /id/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

Mewakili opsi penambahan watermark saat menambahkan watermark ke gambar TIFF.

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | Menginisialisasi instance baru dari kelas [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) class. |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | Menginisialisasi instance baru dari kelas [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) class dengan indeks frame yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Mendapatkan atau mengatur indeks frame untuk menambahkan watermark. |

### Catatan

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Contoh

Tambahkan watermark ke frame tertentu pada gambar TIFF.

```csharp
TiffImageLoadOptions loadOptions = new TiffImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.tiff", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Lihat Juga

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
