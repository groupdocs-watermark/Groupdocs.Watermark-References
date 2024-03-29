---
title: PageMarginType
second_title: .NET API 参考的 GroupDocs.Watermark
description: 获取或设置添加水印时使用的pdf页边距
type: docs
weight: 20
url: /zh/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

获取或设置添加水印时使用的pdf页边距。

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### 适当的价值

添加水印时要使用的 PDF 页边距。

### 评论

此属性仅在[`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins)设置为 true. 如果[`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins)为 false，当 pdf CropBox 用作 水印区域时。

默认值为TrimBox.

### 也可以看看

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* 命名空间 [GroupDocs.Watermark.Contents.Pdf](../../pdfcontent)
* 部件 [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
