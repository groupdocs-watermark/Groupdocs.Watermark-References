---
title: "PresentationContent"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示可以放置水印的 PowerPoint 文档。"
type: docs
weight: 900
url: /zh/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

表示可以放置水印的 PowerPoint 文档。

```csharp
public class PresentationContent : Content
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | 获取此 [`PresentationContent`](../presentationcontent) 的所有布局幻灯片的集合。 |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | 获取此 [`PresentationContent`](../presentationcontent) 的主讲义幻灯片。 |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | 获取此 [`PresentationContent`](../presentationcontent) 的所有备注幻灯片的母版幻灯片。 |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | 获取此 [`PresentationContent`](../presentationcontent) 的所有母版幻灯片的集合。 |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | 获取备注幻灯片的高度（单位：磅）。 |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | 获取备注幻灯片的宽度（单位：磅）。 |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | 获取幻灯片的高度（单位：磅）。 |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | 获取此 [`PresentationContent`](../presentationcontent) 的所有幻灯片的集合。 |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | 获取幻灯片的宽度（单位：磅）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | 解密文档。 |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 释放当前实例。 |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | 加密文档。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 备注

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### 示例

加载和保存任何受支持类型的 PowerPoint 文档。

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // 使用 Add 方法向特定幻灯片或所有幻灯片添加水印。

    // 保存更改。
    watermarker.Save(@"D:\output.ppt");
}
```

### 另请参阅

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
