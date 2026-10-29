---
title: "FromExtension"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Memetakan ekstensi file ke tipe file."
type: docs
weight: 590
url: /id/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

Memetakan ekstensi file ke tipe file.

```csharp
public static FileType FromExtension(string extension)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| extension | String | Ekstensi file (termasuk titik "."). |

### Nilai Kembalian

Ketika tipe file didukung, mengembalikannya; jika tidak, mengembalikan tipe file default [`Unknown`](../unknown).

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *extension* bernilai null atau string kosong. |

### Lihat Juga

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
