---
title: "DiagramContent"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示一个 Visio 文档."
type: docs
weight: 170
url: /zh/net/groupdocs.watermark.contents.diagram/diagramcontent/
---
## DiagramContent class

表示一个 Visio 文档.

```csharp
public sealed class DiagramContent : Content
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [HeaderFooter](../../groupdocs.watermark.contents.diagram/diagramcontent/headerfooter) { get; } | 获取此 [`DiagramContent`](../diagramcontent) 的页眉和页脚。 |
| [Pages](../../groupdocs.watermark.contents.diagram/diagramcontent/pages) { get; } | 获取此 [`DiagramContent`](../diagramcontent) 的所有页面集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 释放当前实例。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 备注

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)
* [Existing objects in diagram document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+diagram+document)

### 另请参阅

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Diagram](../../groupdocs.watermark.contents.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
