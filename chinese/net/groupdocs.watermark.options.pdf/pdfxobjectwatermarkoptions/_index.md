---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示在向 PDF 文档添加 XObject 水印时的水印添加选项。"
type: docs
weight: 1990
url: /zh/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

表示在向 PDF 文档添加 XObject 水印时的水印添加选项。

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | 初始化 [`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | 获取或设置要添加水印的页面索引。 |

### 备注

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### 示例

在 PDF 文档的特定页面上添加水印。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 另请参阅

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
