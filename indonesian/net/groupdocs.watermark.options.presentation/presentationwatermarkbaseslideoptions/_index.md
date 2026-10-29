---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Kelas dasar untuk opsi penambahan watermark ke dokumen Presentation."
type: docs
weight: 2060
url: /id/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

Kelas dasar untuk opsi penambahan watermark ke dokumen Presentation.

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | Mendapatkan atau mengatur teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | Mendapatkan atau mengatur nilai dari [`PresentationImageEffects`](../presentationimageeffects) atau [`PresentationTextEffects`](../presentationtexteffects) untuk efek yang harus diterapkan pada watermark. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | Mendapatkan atau mengatur nama sebuah bentuk. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca. |

### Catatan

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### Contoh

Tambahkan watermark ke slide layanan yang berbeda dari presentasi Power Point.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // Tambahkan watermark ke semua slide master
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // default
    watermarker.Add(watermark, masterSlideOptions);

    // Tambahkan watermark ke semua slide tata letak
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // default
    watermarker.Add(watermark, layoutSlideOptions);

    // Tambahkan watermark ke semua slide catatan
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // default
    watermarker.Add(watermark, noteSlideOptions);

    // Tambahkan watermark ke master handout
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // Tambahkan watermark ke master catatan
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### Lihat Juga

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
