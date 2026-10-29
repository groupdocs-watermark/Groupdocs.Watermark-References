---
title: "Add"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menambahkan watermark ke dokumen yang dimuat."
type: docs
weight: 30
url: /id/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

Menambahkan watermark ke dokumen yang dimuat.

```csharp
public AddWatermarkResult Add(Watermark watermark)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| watermark | Watermark | Watermark yang akan ditambahkan ke dokumen. |

### Catatan

Pelajari lebih lanjut tentang menambahkan watermark: [Adding watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Contoh

Tambahkan watermark gambar dan teks ke dokumen dengan tipe apa pun yang didukung.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.pdf"))
{
    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
    textWatermark.HorizontalAlignment = HorizontalAlignment.Center;
    textWatermark.VerticalAlignment = VerticalAlignment.Top;
    textWatermark.ConsiderParentMargins = true;
    textWatermark.ForegroundColor = Color.Red;
    textWatermark.IsBackground = true;
    textWatermark.Opacity = 0.5;
    watermarker.Add(textWatermark);

    using (ImageWatermark imageWatermark = new ImageWatermark(@"D:\draft.png"))
    {
        imageWatermark.HorizontalAlignment = HorizontalAlignment.Center;
        imageWatermark.VerticalAlignment = VerticalAlignment.Bottom;
        imageWatermark.ConsiderParentMargins = true;
        imageWatermark.IsBackground = true;
        imageWatermark.Opacity = 0.5;
        watermarker.Add(imageWatermark);
    }

    watermarker.Save(@"D:\output.pdf");
}
```

### Lihat Juga

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

Menambahkan watermark ke dokumen yang dimuat menggunakan opsi watermark.

```csharp
public AddWatermarkResult Add(Watermark watermark, WatermarkOptions options)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| watermark | Watermark | Watermark yang akan ditambahkan ke dokumen. |
| options | WatermarkOptions | Opsi tambahan untuk digunakan saat menambahkan watermark. |

### Catatan

Pelajari lebih lanjut tentang menambahkan watermark [Adding watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Contoh

Tambahkan watermark gambar ke halaman tertentu dari dokumen pdf.

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

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
