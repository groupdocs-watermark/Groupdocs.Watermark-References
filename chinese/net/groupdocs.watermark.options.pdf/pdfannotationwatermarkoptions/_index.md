---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示在向 PDF 文档添加注释水印时的水印添加选项。"
type: docs
weight: 1930
url: /zh/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

表示在向 PDF 文档添加注释水印时的水印添加选项。

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | 初始化 [`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | 获取或设置要添加水印的页面索引。 |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | 获取或设置指示是否在 PDF 查看应用程序中打印注释但不显示的值。 |

### 备注

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### 示例

向 PDF 文档添加图像注释水印。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### 另请参阅

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
