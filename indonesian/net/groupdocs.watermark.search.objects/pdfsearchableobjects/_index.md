---
title: "PdfSearchableObjects"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menentukan flag yang mewakili objek konten PDF yang akan disertakan dalam pencarian watermark."
type: docs
weight: 2530
url: /id/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

Menentukan flag yang mewakili objek konten PDF yang akan disertakan dalam pencarian watermark.

```csharp
[Flags]
public enum PdfSearchableObjects
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Menentukan tidak ada objek pencarian. |
| XObjects | `1` | Cari di XObjects. |
| Artifacts | `2` | Cari di artefak. |
| Annotations | `4` | Cari di anotasi. |
| Text | `8` | Cari dalam teks konten. |
| Hyperlinks | `10` | Cari dalam hyperlink. |
| AttachedImages | `20` | Cari di gambar terlampir. |
| Vector | `40` | Cari di operator. |
| All | `7F` | Cari dalam semua objek konten. |

### Lihat Juga

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
