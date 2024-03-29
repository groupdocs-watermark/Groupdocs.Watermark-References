---
title: DiagramShapeWatermarkOptions
second_title: GroupDocs.Watermark untuk Referensi .NET API
description: Mewakili opsi penambahan tanda air saat menambahkan tanda air bentuk ke dokumen Visio.
type: docs
weight: 1680
url: /id/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Mewakili opsi penambahan tanda air saat menambahkan tanda air bentuk ke dokumen Visio.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Menginisialisasi instance baru dari[`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah pengeditan bentuk di Visio dilarang. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Mendapat atau menyetel nilai yang menentukan ke halaman mana tanda air harus ditambahkan. |

### Perkataan

**Belajarlah lagi:**

* [Tambahkan tanda air ke dokumen diagram](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Contoh

Menambahkan tanda air terlindungi ke semua halaman dokumen Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // bawaan

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Lihat juga

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* ruang nama [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* perakitan [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
