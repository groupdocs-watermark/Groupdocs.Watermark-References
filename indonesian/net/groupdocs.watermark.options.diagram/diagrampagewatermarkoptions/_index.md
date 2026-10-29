---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark bentuk ke halaman tertentu dari dokumen Visio."
type: docs
weight: 1720
url: /id/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

Mewakili opsi penambahan watermark saat menambahkan watermark bentuk ke halaman tertentu dari dokumen Visio.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | Menginisialisasi instance baru dari kelas [`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah penyuntingan bentuk di Visio dilarang. |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | Mendapatkan atau mengatur indeks halaman tempat menambahkan watermark. |

### Catatan

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Contoh

Tambahkan watermark terlindungi ke halaman pertama dokumen Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
    options.IsLocked = true;
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Lihat Juga

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
