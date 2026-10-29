---
title: "PdfPage"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示 PDF 文档页面。"
type: docs
weight: 730
url: /zh/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

表示 PDF 文档页面。

```csharp
public class PdfPage : ContentPart
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | 获取此 [`PdfPage`](../pdfpage) 的所有注释的集合。 |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | 获取此 [`PdfPage`](../pdfpage) 的所有伪像的集合。 |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | 获取此 [`PdfPage`](../pdfpage) 的高度（单位为点）。 |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | 获取此 [`PdfPage`](../pdfpage) 的宽度（单位为点）。 |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | 获取此 [`PdfPage`](../pdfpage) 的所有 XObject 的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | 将页面内容转换为图像。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 另请参阅

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
