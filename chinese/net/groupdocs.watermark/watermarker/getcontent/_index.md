---
title: "GetContent"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "返回已加载文档的 Contentgroupdocs.watermark.contents/content 对象。"
type: docs
weight: 60
url: /zh/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

返回已加载文档的 [`Content`](../../../groupdocs.watermark.contents/content) 对象。

```csharp
public T GetContent<T>()
    where T : Content
```

| 参数 | 描述 |
| --- | --- |
| T | 请求的 [`Content`](../../../groupdocs.watermark.contents/content) 对象类型。 |

### 返回值

已加载文档的 [`Content`](../../../groupdocs.watermark.contents/content) 对象。

### 示例

对添加了水印的 PDF 文档页面进行光栅化。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
{ 
    using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
    {
        watermarker.Add(watermark);
    }

    PdfContent content = watermarker.GetContent<PdfContent>();
    content.Rasterize(300, 300, PdfImageConversionFormat.Png);

    watermarker.Save();
}
```

### 另请参阅

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
