---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示 Word 文档中页眉和页脚的集合。"
type: docs
weight: 1370
url: /zh/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/
---
## WordProcessingHeaderFooterCollection class

表示 Word 文档中页眉和页脚的集合。

```csharp
public class WordProcessingHeaderFooterCollection : ReadOnlyListBase<WordProcessingHeaderFooter>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | 获取集合中包含的元素数量。 |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | 获取一个值，指示集合是否为只读。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | 获取集合中指定索引处的元素。 |
| [Item](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/item) { get; } | 获取指定类型的页眉或页脚。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(WordProcessingHeaderFooter) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(WordProcessingHeaderFooter) |  |
| [LinkToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/linktoprevious)(bool) | 将所有页眉和页脚链接或取消链接到前一节中对应的页眉和页脚。 |

### 备注

此集合包含类型为[`WordProcessingHeaderFooter`](../wordprocessingheaderfooter)的项。

### 另请参阅

* class [ReadOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/readonlylistbase-1)
* class [WordProcessingHeaderFooter](../wordprocessingheaderfooter)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
