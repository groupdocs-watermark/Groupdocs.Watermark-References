---
title: "GetImages"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan."
type: docs
weight: 80
url: /id/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan.

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | Kriteria pencarian yang akan digunakan. |

### Nilai Kembalian

Koleksi gambar yang ditemukan.

### Catatan

Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../searchableobjects).

Pelajari lebih lanjut tentang mencari watermark [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Contoh

Hapus semua gambar yang mirip dengan referensi dari dokumen dengan tipe apa pun yang didukung.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Lihat Juga

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

Menemukan semua gambar dalam dokumen.

```csharp
public WatermarkableImageCollection GetImages()
```

### Nilai Kembalian

Koleksi gambar yang ditemukan.

### Catatan

Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../searchableobjects).

Pelajari lebih lanjut tentang mencari watermark [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Contoh

Tambahkan watermark ke semua gambar dalam dokumen dengan tipe apa pun yang didukung.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Inisialisasi watermark teks atau gambar.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Temukan semua gambar dalam dokumen.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Tambahkan watermark.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // Simpan perubahan.
    watermarker.Save(@"D:\output.doc");
}
```

### Lihat Juga

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
