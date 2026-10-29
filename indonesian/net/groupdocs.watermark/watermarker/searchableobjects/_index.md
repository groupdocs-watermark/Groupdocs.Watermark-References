---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mendapatkan atau mengatur objek konten yang akan dimasukkan dalam pencarian watermark."
type: docs
weight: 20
url: /id/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

Mendapatkan atau mengatur objek konten yang akan dimasukkan dalam pencarian watermark.

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

Objek-objek yang akan dimasukkan dalam pencarian watermark.

### Catatan

Properti ini juga menentukan objek konten yang digunakan dalam pencarian gambar. Untuk informasi lebih lanjut lihat metode [`Search`](../search) dan [`GetImages`](../getimages).

Pelajari lebih lanjut tentang pencarian watermark: [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Contoh

Hapus semua XObjects dan Artifacts dari dokumen pdf.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // Tentukan bahwa hanya XObjects dan Artifacts yang harus dicari.
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // Hapus semua objek yang ditemukan.
    watermarks.Clear();

    // Simpan perubahan.
    watermarker.Save();
}
```

### Lihat Juga

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
