---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menentukan flag yang mewakili objek pesan email yang akan disertakan dalam pencarian watermark."
type: docs
weight: 2520
url: /id/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

Menentukan flag yang mewakili objek pesan email yang akan disertakan dalam pencarian watermark.

```csharp
[Flags]
public enum EmailSearchableObjects
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Menentukan tidak ada objek pencarian. |
| Subject | `1` | Cari di subjek pesan. |
| PlainTextBody | `2` | Cari di isi pesan teks biasa. |
| HtmlBody | `4` | Cari di isi pesan HTML. |
| AttachedImages | `8` | Cari di gambar terlampir. |
| EmbeddedImages | `10` | Cari di gambar tersemat. |
| All | `1F` | Cari di semua objek email. |

### Lihat Juga

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
