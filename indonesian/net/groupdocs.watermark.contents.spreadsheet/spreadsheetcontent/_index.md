---
title: "SpreadsheetContent"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili dokumen Excel tempat watermark dapat ditempatkan."
type: docs
weight: 1170
url: /id/net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
---
## SpreadsheetContent class

Mewakili dokumen Excel tempat watermark dapat ditempatkan.

```csharp
public class SpreadsheetContent : Content
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Worksheets](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets) { get; } | Mendapatkan koleksi semua lembar kerja dari [`SpreadsheetContent`](../spreadsheetcontent) ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt)() | Mendekripsi dokumen. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Membuang instance saat ini. |
| [Encrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt)(string) | Mengenkripsi konten. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Menemukan semua gambar dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Menemukan semua watermark yang mungkin dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Catatan

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)
* [Shapes in spreadsheet document](https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document)
* [Working with spreadsheet document attachments](https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments)
* [Working with worksheet backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds)
* [Working with worksheet headers and footers](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers)

### Contoh

Muat dan simpan dokumen Excel dari tipe apa pun yang didukung.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.xls", loadOptions))
{
    // Gunakan metode Add untuk menambahkan watermark ke lembar kerja tertentu atau semua lembar kerja.

    // Simpan perubahan.
    watermarker.Save(@"D:\output.xls");
}
```

### Lihat Juga

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
