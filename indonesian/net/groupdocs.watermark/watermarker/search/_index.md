---
title: "Search"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menelusuri semua watermark yang mungkin dalam dokumen."
type: docs
weight: 110
url: /id/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

Menelusuri semua watermark yang mungkin dalam dokumen.

```csharp
public PossibleWatermarkCollection Search()
```

### Nilai Kembalian

Koleksi watermark yang mungkin.

### Catatan

Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../searchableobjects).

Pelajari lebih lanjut tentang mencari watermark [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Contoh

Hitung watermark yang mungkin dalam dokumen dengan tipe apa pun yang didukung.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### Lihat Juga

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

Menelusuri watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan.

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| searchCriteria | SearchCriteria | Kriteria pencarian yang akan digunakan. |

### Nilai Kembalian

Koleksi watermark yang mungkin.

### Catatan

Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../searchableobjects).

Pelajari lebih lanjut tentang mencari watermark [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Contoh

Temukan dan hapus semua watermark yang mungkin yang berisi teks atau gambar tertentu dari dokumen dengan tipe apa pun yang didukung.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarks.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Lihat Juga

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
