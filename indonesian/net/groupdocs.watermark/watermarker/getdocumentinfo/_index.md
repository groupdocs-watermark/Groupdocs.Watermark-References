---
title: "GetDocumentInfo"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mendapatkan informasi tentang format dokumen yang dimuat."
type: docs
weight: 70
url: /id/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

Mendapatkan informasi tentang format dokumen yang dimuat.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Nilai Kembalian

Instansi [`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo) yang berisi informasi yang terdeteksi.

### Catatan

Pelajari lebih lanjut tentang mendapatkan informasi dokumen [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info).

### Contoh

Dapatkan informasi tentang dokumen dengan tipe apa pun yang didukung.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.ppt"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Lihat Juga

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
