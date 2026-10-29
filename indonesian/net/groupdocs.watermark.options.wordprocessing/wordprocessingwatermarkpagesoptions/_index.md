---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili opsi saat menambahkan watermark ke halaman dokumen Word."
type: docs
weight: 2410
url: /id/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

Mewakili opsi saat menambahkan watermark ke halaman dokumen Word.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | Menginisialisasi instance baru dari kelas [`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Mendapatkan atau mengatur teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Mendapatkan atau mengatur nilai dari [`WordProcessingImageEffects`](../wordprocessingimageeffects) atau [`WordProcessingTextEffects`](../wordprocessingtexteffects) untuk efek yang harus diterapkan pada watermark. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah penyuntingan bentuk di Word dilarang. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Mendapatkan atau mengatur tipe kunci watermark. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Mendapatkan atau mengatur nama sebuah bentuk. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | Mendapatkan atau mengatur nomor halaman untuk menambahkan watermark. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Mendapatkan atau mengatur kata sandi yang digunakan untuk mengunci watermark. |

### Catatan

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Contoh

Tambahkan watermark ke halaman tertentu dalam dokumen Word.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("text", new Font("Arial", 42));

    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
    options.PageNumbers = new[] { 1 };

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Lihat Juga

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
