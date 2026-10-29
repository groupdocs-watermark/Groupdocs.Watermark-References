---
title: "GifImageContent"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示可以放置水印的 GIF 图像。"
type: docs
weight: 390
url: /zh/net/groupdocs.watermark.contents.image/gifimagecontent/
---
## GifImageContent class

表示可以放置水印的 GIF 图像。

```csharp
public sealed class GifImageContent : MultiframeImageContent
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Frames](../../groupdocs.watermark.contents.image/multiframeimagecontent/frames) { get; } | 获取图像的所有帧的集合。 |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | 获取此[`ImageContent`](../imagecontent)的高度（像素）。 |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | 获取此[`ImageContent`](../imagecontent)的宽度（像素）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 释放当前实例。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 另请参阅

* class [MultiframeImageContent](../multiframeimagecontent)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
