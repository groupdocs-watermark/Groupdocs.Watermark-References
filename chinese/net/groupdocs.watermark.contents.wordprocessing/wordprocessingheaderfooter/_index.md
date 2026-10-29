---
title: "WordProcessingHeaderFooter"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示 Word 文档中的页眉/页脚。"
type: docs
weight: 1360
url: /zh/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/
---
## WordProcessingHeaderFooter class

表示 Word 文档中的页眉/页脚。

```csharp
public class WordProcessingHeaderFooter : ContentPart
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [HeaderFooterType](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/headerfootertype) { get; } | 获取此[`WordProcessingHeaderFooter`](../wordprocessingheaderfooter)的类型。 |
| [IsLinkedToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/islinkedtoprevious) { get; set; } | 获取或设置一个值，指示此页眉/页脚是否链接到前一节中对应的页眉/页脚。 |
| [Section](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/section) { get; } | 获取此[`WordProcessingHeaderFooter`](../wordprocessingheaderfooter)的父节。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 另请参阅

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
