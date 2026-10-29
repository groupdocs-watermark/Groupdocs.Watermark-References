---
title: "SizingType"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menentukan bagaimana ukuran watermark harus dihitung."
type: docs
weight: 3300
url: /id/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

Menentukan bagaimana ukuran watermark harus dihitung.

```csharp
public enum SizingType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | Watermark harus diukur secara otomatis sesuai dengan kontennya. |
| Absolute | `1` | Watermark harus diukur ke [`Width`](../../groupdocs.watermark/watermark/width) dan [`Height`](../../groupdocs.watermark/watermark/height) yang tepat. |
| ScaleToParentDimensions | `2` | Watermark harus diskalakan relatif terhadap dimensi induk menggunakan [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) yang ditentukan. |
| ScaleToParentArea | `3` | Watermark harus diskalakan relatif terhadap area induk menggunakan [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) yang ditentukan. |

### Lihat Juga

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
