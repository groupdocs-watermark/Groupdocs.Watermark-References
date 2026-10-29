---
title: "PageMarginType"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "获取或设置在添加水印时使用的 PDF 页面边距。"
type: docs
weight: 20
url: /zh/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

获取或设置在添加水印时使用的 PDF 页面边距。

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

在添加水印期间使用的 PDF 页面边距。

### 备注

此属性仅在 [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) 设置为 true 时有效。如果 [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) 为 false，则使用 PDF CropBox 作为水印区域。

默认值为 TrimBox。

### 另请参阅

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
