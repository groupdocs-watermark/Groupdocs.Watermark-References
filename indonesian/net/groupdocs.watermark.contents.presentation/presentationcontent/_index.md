---
title: "PresentationContent"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili dokumen PowerPoint di mana watermark dapat ditempatkan."
type: docs
weight: 900
url: /id/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

Mewakili dokumen PowerPoint di mana watermark dapat ditempatkan.

```csharp
public class PresentationContent : Content
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | Mendapatkan koleksi semua slide tata letak dari [`PresentationContent`](../presentationcontent) ini. |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | Mendapatkan slide handout master dari [`PresentationContent`](../presentationcontent) ini. |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | Mendapatkan slide master untuk semua slide catatan dari [`PresentationContent`](../presentationcontent) ini. |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | Mendapatkan koleksi semua slide master dari [`PresentationContent`](../presentationcontent) ini. |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | Mendapatkan tinggi slide catatan dalam poin. |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | Mendapatkan lebar slide catatan dalam poin. |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | Mendapatkan tinggi slide dalam poin. |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | Mendapatkan koleksi semua slide dari [`PresentationContent`](../presentationcontent) ini. |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | Mendapatkan lebar slide dalam poin. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | Mendekripsi dokumen. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Membuang instance saat ini. |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | Mengenkripsi dokumen. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Menemukan semua gambar dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Menemukan semua watermark yang mungkin dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Catatan

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### Contoh

Muat dan simpan dokumen PowerPoint dari jenis yang didukung apa pun.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // Gunakan metode Add untuk menambahkan watermark ke slide tertentu atau semua slide.

    // Simpan perubahan.
    watermarker.Save(@"D:\output.ppt");
}
```

### Lihat Juga

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
