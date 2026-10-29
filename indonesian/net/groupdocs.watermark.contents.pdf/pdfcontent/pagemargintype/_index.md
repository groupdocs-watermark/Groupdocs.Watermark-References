---
title: "PageMarginType"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mendapatkan atau mengatur margin halaman pdf yang akan digunakan selama penambahan watermark."
type: docs
weight: 20
url: /id/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

Mendapatkan atau mengatur margin halaman pdf yang akan digunakan selama penambahan watermark.

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

Margin halaman PDF yang akan digunakan selama penambahan watermark.

### Catatan

Properti ini hanya berfungsi ketika [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) diatur ke true. Jika [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) false, maka pdf CropBox digunakan sebagai area watermark.

Nilai default adalah TrimBox.

### Lihat Juga

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
