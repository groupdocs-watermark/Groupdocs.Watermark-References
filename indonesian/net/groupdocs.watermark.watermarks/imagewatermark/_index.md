---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili watermark gambar."
type: docs
weight: 3190
url: /id/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

Mewakili watermark gambar.

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | Menginisialisasi sebuah instance baru dari kelas [`ImageWatermark`](../imagewatermark) dengan aliran yang ditentukan. |
| [ImageWatermark](imagewatermark#constructor_1)(string) | Menginisialisasi sebuah instance baru dari kelas [`ImageWatermark`](../imagewatermark) dengan jalur file yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Mengambil atau mengatur nilai yang menunjukkan apakah ukuran dan koordinat watermark dihitung dengan mempertimbangkan margin induk. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Mendapatkan atau mengatur tinggi yang diinginkan dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Mendapatkan atau mengatur perataan horizontal dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah watermark harus ditempatkan di latar belakang. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Mendapatkan atau mengatur pengaturan margin dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Mendapatkan atau mengatur opasitas dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Mendapatkan atau mengatur pengaturan penyiapan halaman dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Mendapatkan atau mengatur sudut rotasi dari [`Watermark`](../../groupdocs.watermark/watermark) ini dalam derajat. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah informasi tentang watermark yang ditambahkan harus disimpan dalam metadata dokumen. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Mendapatkan atau mengatur nilai yang menentukan bagaimana ukuran watermark bergantung pada ukuran induk. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Mendapatkan atau mengatur nilai yang menentukan cara ukuran watermark. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Mendapatkan atau mengatur opsi untuk mendefinisikan watermark berulang. |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Mendapatkan atau mengatur perataan vertikal dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Mendapatkan atau mengatur lebar yang diinginkan dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Mendapatkan atau mengatur koordinat x dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Mendapatkan atau mengatur koordinat y dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | Membuang instance saat ini. |

### Catatan

**Learn more:**

* [Adding image watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### Contoh

Tambahkan watermark gambar ke dokumen dengan tipe apa pun yang didukung.

```csharp
foreach (string filePath in Directory.GetFiles(@"C:\Documents"))
{
    using (Watermarker watermarker = new Watermarker(filePath))
    {
        using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
        {
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            watermarker.Add(watermark);
        }

        watermarker.Save();
    }
}
```

### Lihat Juga

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
