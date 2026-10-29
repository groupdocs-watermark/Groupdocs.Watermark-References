---
title: "GetContent"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mengembalikan objek Contentgroupdocs.watermark.contents/content untuk dokumen yang dimuat."
type: docs
weight: 60
url: /id/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

Mengembalikan objek [`Content`](../../../groupdocs.watermark.contents/content) untuk dokumen yang dimuat.

```csharp
public T GetContent<T>()
    where T : Content
```

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe yang diminta dari objek [`Content`](../../../groupdocs.watermark.contents/content). |

### Nilai Kembalian

Objek [`Content`](../../../groupdocs.watermark.contents/content) untuk dokumen yang dimuat.

### Contoh

Rasterkan halaman dokumen pdf dengan watermark yang ditambahkan.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
{ 
    using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
    {
        watermarker.Add(watermark);
    }

    PdfContent content = watermarker.GetContent<PdfContent>();
    content.Rasterize(300, 300, PdfImageConversionFormat.Png);

    watermarker.Save();
}
```

### Lihat Juga

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
