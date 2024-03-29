---
title: WordProcessingWatermarkPagesOptions
second_title: GroupDocs.Watermark untuk Referensi .NET API
description: Mewakili opsi saat menambahkan watermark ke halaman dokumen Word.
type: docs
weight: 2370
url: /id/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

Mewakili opsi saat menambahkan watermark ke halaman dokumen Word.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | Menginisialisasi instance baru dari[`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Mendapatkan atau menyetel teks deskriptif (alternatif) yang akan dikaitkan dengan bentuk. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Mendapat atau menetapkan nilai[`WordProcessingImageEffects`](../wordprocessingimageeffects) or [`WordProcessingTextEffects`](../wordprocessingtexteffects) untuk efek yang harus diterapkan pada watermark. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah pengeditan bentuk di Word dilarang. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Mendapat atau menyetel jenis kunci tanda air. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Mendapatkan atau menyetel nama menjadi bentuk. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | Mendapat atau mengatur nomor halaman untuk menambahkan watermark. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Mendapatkan atau menyetel kata sandi yang digunakan untuk mengunci tanda air. |

### Perkataan

**Belajarlah lagi:**

* [Tambahkan watermark ke dokumen pengolah kata](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Contoh

Tambahkan watermark ke halaman tertentu dari dokumen Word.

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

### Lihat juga

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* ruang nama [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* perakitan [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
