---
title: "Remove"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menghapus watermark dari dokumen."
type: docs
weight: 90
url: /id/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

Menghapus watermark dari dokumen.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | Watermark yang akan dihapus. |

### Catatan

Pelajari lebih lanjut tentang menghapus watermark: [Removing found watermarks](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Contoh

Temukan dan hapus watermark pertama yang memungkinkan yang berisi teks atau gambar tertentu dari dokumen dengan tipe apa pun yang didukung.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    if (watermarks.Count > 0)
    {
        watermarker.Remove(watermarks[0]);
    }

    watermarker.Save(@"D:\output.doc");
}
```

### Lihat Juga

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

Menghapus semua watermark dalam koleksi dari dokumen.

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | Koleksi watermark yang akan dihapus. |

### Catatan

Pelajari lebih lanjut tentang menghapus watermark [Removing found watermarks](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### Contoh

Temukan dan hapus semua watermark yang mungkin yang berisi teks atau gambar tertentu dari dokumen dengan tipe apa pun yang didukung.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarker.Remove(watermarks);
    watermarker.Save(@"D:\output.doc");
}
```

### Lihat Juga

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
