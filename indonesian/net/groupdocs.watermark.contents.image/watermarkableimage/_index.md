---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili gambar di dalam dokumen."
type: docs
weight: 470
url: /id/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

Mewakili gambar di dalam dokumen.

```csharp
public abstract class WatermarkableImage : ContentPart
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Mendapatkan tinggi dari [`WatermarkableImage`](../watermarkableimage) ini dalam piksel. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Mendapatkan lebar dari [`WatermarkableImage`](../watermarkableimage) ini dalam piksel. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Menambahkan watermark ke [`WatermarkableImage`](../watermarkableimage) ini. Metode ini mengasumsikan bahwa offset dan ukuran watermark diukur dalam piksel (jika telah ditetapkan). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Menemukan semua gambar dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Mendapatkan gambar sebagai array byte. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Menemukan semua watermark yang mungkin dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Catatan

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### Contoh

Tambahkan watermark ke semua gambar dalam dokumen dengan tipe apa pun yang didukung.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Inisialisasi watermark teks atau gambar.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Temukan semua gambar dalam konten.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Tambahkan watermark.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // Simpan perubahan.
    watermarker.Save(@"D:\output.doc");
}
```

### Lihat Juga

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
