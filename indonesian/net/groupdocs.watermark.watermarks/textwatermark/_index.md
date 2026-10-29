---
title: "TextWatermark"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili watermark teks."
type: docs
weight: 3320
url: /id/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Mewakili watermark teks.

```csharp
public class TextWatermark : Watermark
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Menginisialisasi instance baru dari kelas [`TextWatermark`](../textwatermark) dengan teks dan font yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Mendapatkan atau mengatur warna latar belakang teks. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Mengambil atau mengatur nilai yang menunjukkan apakah ukuran dan koordinat watermark dihitung dengan mempertimbangkan margin induk. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Mendapatkan atau mengatur font teks. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Mendapatkan atau mengatur warna latar depan teks. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Mendapatkan atau mengatur tinggi yang diinginkan dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Mendapatkan atau mengatur perataan horizontal dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah watermark harus ditempatkan di latar belakang. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Mendapatkan atau mengatur pengaturan margin dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Mendapatkan atau mengatur opasitas dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Mendapatkan atau mengatur pengaturan padding dari [`TextWatermark`](../textwatermark) ini. Properti ini hanya berlaku untuk file gambar. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Mendapatkan atau mengatur pengaturan penyiapan halaman dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Mendapatkan atau mengatur sudut rotasi dari [`Watermark`](../../groupdocs.watermark/watermark) ini dalam derajat. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah informasi tentang watermark yang ditambahkan harus disimpan dalam metadata dokumen. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Mendapatkan atau mengatur nilai yang menentukan bagaimana ukuran watermark bergantung pada ukuran induk. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Mendapatkan atau mengatur nilai yang menentukan cara ukuran watermark. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Mendapatkan atau mengatur teks yang akan digunakan sebagai watermark. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Mendapatkan atau mengatur perataan teks watermark. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Mendapatkan atau mengatur opsi untuk mendefinisikan watermark berulang. |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Mendapatkan atau mengatur perataan vertikal dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Mendapatkan atau mengatur lebar yang diinginkan dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Mendapatkan atau mengatur koordinat x dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Mendapatkan atau mengatur koordinat y dari [`Watermark`](../../groupdocs.watermark/watermark) ini. |

### Catatan

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Contoh

Skala watermark teks tergantung pada ukuran induk.

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### Lihat Juga

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
