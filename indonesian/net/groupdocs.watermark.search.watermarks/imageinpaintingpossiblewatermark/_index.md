---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili wilayah gambar yang ditentukan secara manual yang harus diisi dengan inpainting menggunakan piksel di sekitarnya."
type: docs
weight: 2900
url: /id/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

Mewakili wilayah gambar yang ditentukan secara manual yang harus diisi ulang (diisi menggunakan piksel di sekitarnya).

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | Menginisialisasi instance baru dari kelas [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | Mendapatkan koleksi fragmen teks terformat dari [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) ini. |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | Mendapatkan tinggi dari [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) ini. |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Mendapatkan atau mengatur gambar dari [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) ini. |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | Mendapatkan atau mengatur algoritma inpainting. Defaultnya adalah PatchBased. |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | Mendapatkan halaman tempat watermark ditempatkan. |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | Mendapatkan induk dari [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark) ini. Selalu mengembalikan `null` karena wilayah ditentukan secara manual. |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | Mendapatkan atau mengatur ukuran patch yang digunakan oleh algoritma (ganjil, 5-11). Defaultnya adalah 7. Untuk Telea ini digunakan sebagai HalfPatchSize. |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | Mendapatkan atau mengatur wilayah poligonal yang akan di‑inpaint, dalam piksel gambar. Setiap poligon adalah array dari titik‑titik sudut. Harus menentukan salah satu antara [`Rectangles`](./rectangles) atau [`Polygons`](./polygons), tetapi tidak keduanya. |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | Mendapatkan atau mengatur area persegi panjang yang akan di‑inpaint, dalam piksel gambar. Harus menentukan salah satu antara [`Rectangles`](./rectangles) atau [`Polygons`](./polygons), tetapi tidak keduanya. |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | Mendapatkan sudut rotasi dari [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) ini dalam derajat. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | Mendapatkan atau mengatur teks dari [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) ini. |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | Mendapatkan satuan ukuran dari [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) ini. |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | Mendapatkan lebar dari [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) ini. |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | Mendapatkan koordinat x dari [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) ini. |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | Mendapatkan koordinat y dari [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) ini. |

### Lihat Juga

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
