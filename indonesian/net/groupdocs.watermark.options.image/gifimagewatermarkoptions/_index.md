---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark ke gambar GIF."
type: docs
weight: 1830
url: /id/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

Mewakili opsi penambahan watermark saat menambahkan watermark ke gambar GIF.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | Menginisialisasi instance baru dari kelas [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) class. |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | Menginisialisasi instance baru dari kelas [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) class dengan indeks frame yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Mendapatkan atau mengatur indeks frame untuk menambahkan watermark. |

### Catatan

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Contoh

Tambahkan watermark ke frame tertentu pada gambar GIF.

```csharp
GifImageLoadOptions loadOptions = new GifImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
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
