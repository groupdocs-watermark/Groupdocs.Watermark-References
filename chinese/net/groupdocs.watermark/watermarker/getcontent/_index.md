---
title: GetContent
second_title: .NET API 参考的 GroupDocs.Watermark
description: 返回Contentgroupdocs.watermark.contents/content加载文档的对象
type: docs
weight: 60
url: /zh/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

返回[`Content`](../../../groupdocs.watermark.contents/content)加载文档的对象。

```csharp
public T GetContent<T>()
    where T : Content
```

| 范围 | 描述 |
| --- | --- |
| T | 请求的类型[`Content`](../../../groupdocs.watermark.contents/content)目的。 |

### 返回值

这[`Content`](../../../groupdocs.watermark.contents/content)加载文档的对象。

### 例子

光栅化 pdf 文档页面并添加水印。

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

### 也可以看看

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->