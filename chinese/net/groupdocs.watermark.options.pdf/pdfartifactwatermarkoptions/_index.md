---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示在向 PDF 文档添加工件水印时的水印添加选项。"
type: docs
weight: 1940
url: /zh/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

表示在向 PDF 文档添加工件水印时的水印添加选项。

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | 初始化 [`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | 获取或设置要添加水印的页面索引。 |

### 备注

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### 示例

向 PDF 文档添加图像工件水印。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### 另请参阅

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
