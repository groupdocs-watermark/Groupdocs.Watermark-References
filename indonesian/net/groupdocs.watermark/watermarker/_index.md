---
title: Watermarker
second_title: GroupDocs.Watermark untuk Referensi .NET API
description: Mewakili kelas untuk manajemen watermark dalam dokumen.
type: docs
weight: 3060
url: /id/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Mewakili kelas untuk manajemen watermark dalam dokumen.

```csharp
public class Watermarker : IDisposable
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Menginisialisasi instance baru dari[`Watermarker`](../watermarker) kelas dengan aliran yang ditentukan. |
| [Watermarker](watermarker#constructor_4)(string) | Menginisialisasi instance baru dari[`Watermarker`](../watermarker) kelas dengan jalur dokumen yang ditentukan. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Menginisialisasi instance baru dari[`Watermarker`](../watermarker) kelas dengan stream yang ditentukan dan opsi muat. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Menginisialisasi instance baru dari[`Watermarker`](../watermarker) kelas dengan stream dan pengaturan yang ditentukan. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Menginisialisasi instance baru dari[`Watermarker`](../watermarker)kelas dengan jalur dokumen yang ditentukan dan memuat opsi. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Menginisialisasi instance baru dari[`Watermarker`](../watermarker) kelas dengan jalur dan pengaturan dokumen yang ditentukan. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Menginisialisasi instance baru dari[`Watermarker`](../watermarker) kelas dengan aliran yang ditentukan, memuat opsi dan pengaturan. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Menginisialisasi instance baru dari[`Watermarker`](../watermarker) kelas dengan jalur dokumen yang ditentukan , memuat opsi dan pengaturan. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Mendapat atau menyetel objek konten yang akan disertakan dalam pencarian watermark. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Menambahkan tanda air ke dokumen yang dimuat. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Menambahkan tanda air ke dokumen yang dimuat menggunakan opsi tanda air. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Membuang instance saat ini. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Menghasilkan gambar pratinjau untuk dokumen. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Mengembalikan[`Content`](../../groupdocs.watermark.contents/content) objek untuk dokumen yang dimuat. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Mendapat informasi tentang format dokumen yang dimuat. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Menemukan semua gambar dalam dokumen. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Menemukan gambar menurut kriteria pencarian yang ditentukan. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Menghilangkan watermark dari dokumen. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Menghapus semua watermark dalam koleksi dari dokumen. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Menyimpan data dokumen ke aliran yang mendasarinya. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Menyimpan data dokumen ke aliran dasar menggunakan opsi penyimpanan. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Menyimpan dokumen ke aliran yang ditentukan. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Menyimpan dokumen ke lokasi file yang ditentukan. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Menyimpan dokumen ke aliran yang ditentukan menggunakan opsi simpan. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Menyimpan dokumen ke lokasi file yang ditentukan menggunakan opsi penyimpanan. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Mencari semua kemungkinan tanda air dalam dokumen. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Mencari kemungkinan tanda air sesuai dengan kriteria pencarian yang ditentukan. |

### Contoh

Memuat dan menyimpan konten dalam format apa pun yang didukung.

```csharp
// Memuat konten dari file.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Gunakan metode kelas Watermarker untuk menambah, mencari, atau menghapus tanda air.

    // Simpan perubahan.
    watermarker.Save("D:\\output.pdf");
}
```

### Lihat juga

* ruang nama [GroupDocs.Watermark](../../groupdocs.watermark)
* perakitan [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
