---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mendefinisikan metode yang diperlukan untuk mendapatkan informasi dasar dokumen."
type: docs
weight: 70
url: /id/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

Mendefinisikan metode yang diperlukan untuk mendapatkan informasi dasar dokumen.

```csharp
public interface IDocumentInfo
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | Mendapatkan deskripsi format file. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | Mendapatkan nilai yang menunjukkan apakah dokumen terenkripsi dan memerlukan kata sandi untuk dibuka. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | Mendapatkan total jumlah halaman. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | Mendapatkan koleksi deskripsi halaman dokumen. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | Mendapatkan ukuran dokumen dalam byte. |

### Catatan

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Contoh

Contoh berikut menunjukkan cara mengambil informasi dokumen umum menggunakan [`IDocumentInfo`](../idocumentinfo).

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Lihat Juga

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
