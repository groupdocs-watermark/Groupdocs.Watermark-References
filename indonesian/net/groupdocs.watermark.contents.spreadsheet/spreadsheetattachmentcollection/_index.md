---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili kumpulan lampiran dalam dokumen Excel."
type: docs
weight: 1110
url: /id/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/
---
## SpreadsheetAttachmentCollection class

Mewakili kumpulan lampiran dalam dokumen Excel.

```csharp
public class SpreadsheetAttachmentCollection : RemoveOnlyListBase<SpreadsheetAttachment>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Mendapatkan jumlah elemen yang terdapat dalam koleksi. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi hanya-baca. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Mendapatkan elemen pada indeks yang ditentukan dalam koleksi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddAttachment](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment)(byte[], string, byte[], double, double, double, double) | Menambahkan lampiran ke [`SpreadsheetWorksheet`](../spreadsheetworksheet). |
| [AddLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink)(string, byte[], double, double, double, double) | Menambahkan lampiran melalui tautan (dokumen tidak akan berisi konten file yang dilampirkan). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(SpreadsheetAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(SpreadsheetAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(SpreadsheetAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Catatan

Koleksi ini berisi item dengan tipe [`SpreadsheetAttachment`](../spreadsheetattachment).

### Lihat Juga

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [SpreadsheetAttachment](../spreadsheetattachment)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
