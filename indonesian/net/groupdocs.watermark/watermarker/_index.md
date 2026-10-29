---
title: "Watermarker"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili kelas untuk manajemen watermark dalam dokumen."
type: docs
weight: 3140
url: /id/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Mewakili kelas untuk manajemen watermark dalam dokumen.

```csharp
public class Watermarker : IDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Menginisialisasi instance baru dari kelas [`Watermarker`](../watermarker) dengan aliran yang ditentukan. |
| [Watermarker](watermarker#constructor_4)(string) | Menginisialisasi instance baru dari kelas [`Watermarker`](../watermarker) dengan jalur dokumen yang ditentukan. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Menginisialisasi instance baru dari kelas [`Watermarker`](../watermarker) dengan aliran yang ditentukan dan opsi pemuatan. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Menginisialisasi instance baru dari kelas [`Watermarker`](../watermarker) dengan aliran yang ditentukan dan pengaturan. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Menginisialisasi instance baru dari kelas [`Watermarker`](../watermarker) dengan jalur dokumen yang ditentukan dan opsi pemuatan. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Menginisialisasi instance baru dari kelas [`Watermarker`](../watermarker) dengan jalur dokumen yang ditentukan dan pengaturan. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Menginisialisasi instance baru dari kelas [`Watermarker`](../watermarker) dengan aliran yang ditentukan, opsi pemuatan, dan pengaturan. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Menginisialisasi instance baru dari kelas [`Watermarker`](../watermarker) dengan jalur dokumen yang ditentukan, opsi pemuatan, dan pengaturan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Mendapatkan atau mengatur objek konten yang akan dimasukkan dalam pencarian watermark. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Menambahkan watermark ke dokumen yang dimuat. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Menambahkan watermark ke dokumen yang dimuat menggunakan opsi watermark. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Membuang instance saat ini. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Menghasilkan gambar pratinjau untuk dokumen. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Mengembalikan objek [`Content`](../../groupdocs.watermark.contents/content) untuk dokumen yang dimuat. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Mendapatkan informasi tentang format dokumen yang dimuat. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Menemukan semua gambar dalam dokumen. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Menghapus watermark dari dokumen. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Menghapus semua watermark dalam koleksi dari dokumen. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Menyimpan data dokumen ke aliran dasar. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Menyimpan data dokumen ke aliran dasar menggunakan opsi penyimpanan. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Menyimpan dokumen ke aliran yang ditentukan. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Menyimpan dokumen ke lokasi file yang ditentukan. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Menyimpan dokumen ke aliran yang ditentukan menggunakan opsi penyimpanan. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Menyimpan dokumen ke lokasi file yang ditentukan menggunakan opsi penyimpanan. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Menelusuri semua watermark yang mungkin dalam dokumen. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Menelusuri watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. |

### Contoh

Muat dan simpan konten dalam format apa pun yang didukung.

```csharp
// Muat konten dari sebuah file.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Gunakan metode kelas Watermarker untuk menambahkan, mencari, atau menghapus watermark.

    // Simpan perubahan.
    watermarker.Save("D:\\output.pdf");
}
```

### Lihat Juga

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
