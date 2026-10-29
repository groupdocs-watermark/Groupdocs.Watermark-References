---
title: "PresentationNotesSlide"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示 PowerPoint 文档的备注幻灯片。"
type: docs
weight: 1010
url: /zh/net/groupdocs.watermark.contents.presentation/presentationnotesslide/
---
## PresentationNotesSlide class

表示 PowerPoint 文档的备注幻灯片。

```csharp
public class PresentationNotesSlide : PresentationBaseSlide
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Charts](../../groupdocs.watermark.contents.presentation/presentationbaseslide/charts) { get; } | 获取演示文稿中所有图表的集合。 |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseslide/imagefillformat) { get; } | 获取演示文稿的图像填充格式设置。 |
| [Shapes](../../groupdocs.watermark.contents.presentation/presentationbaseslide/shapes) { get; } | 获取演示文稿中所有形状的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 另请参阅

* class [PresentationBaseSlide](../presentationbaseslide)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
