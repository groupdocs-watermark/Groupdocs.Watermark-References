---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili opsi saat menambahkan watermark bentuk ke bagian dokumen Word."
type: docs
weight: 2420
url: /id/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/
---
## WordProcessingWatermarkSectionOptions class

Mewakili opsi saat menambahkan watermark bentuk ke bagian dokumen Word.

```csharp
public sealed class WordProcessingWatermarkSectionOptions : WordProcessingWatermarkBaseOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WordProcessingWatermarkSectionOptions](wordprocessingwatermarksectionoptions)() | Menginisialisasi instance baru dari kelas [`WordProcessingWatermarkSectionOptions`](../wordprocessingwatermarksectionoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Mendapatkan atau mengatur teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Mendapatkan atau mengatur nilai dari [`WordProcessingImageEffects`](../wordprocessingimageeffects) atau [`WordProcessingTextEffects`](../wordprocessingtexteffects) untuk efek yang harus diterapkan pada watermark. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah penyuntingan bentuk di Word dilarang. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Mendapatkan atau mengatur tipe kunci watermark. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Mendapatkan atau mengatur nama sebuah bentuk. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Mendapatkan atau mengatur kata sandi yang digunakan untuk mengunci watermark. |
| [SectionIndex](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/sectionindex) { get; set; } | Mendapatkan atau mengatur indeks bagian untuk menambahkan watermark. |

### Catatan

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Contoh

Tambahkan watermark ke bagian tertentu dalam dokumen Word.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;
    watermark.ForegroundColor = Color.Red;

    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
    options.SectionIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Lihat Juga

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
