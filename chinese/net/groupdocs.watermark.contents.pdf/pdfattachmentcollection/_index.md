---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示 PDF 文档中附件的集合。"
type: docs
weight: 650
url: /zh/net/groupdocs.watermark.contents.pdf/pdfattachmentcollection/
---
## PdfAttachmentCollection class

表示 PDF 文档中附件的集合。

```csharp
public class PdfAttachmentCollection : RemoveOnlyListBase<PdfAttachment>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | 获取集合中包含的元素数量。 |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | 获取一个值，指示集合是否为只读。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | 获取集合中指定索引处的元素。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.pdf/pdfattachmentcollection/add)(byte[], string, string) | 向 [`PdfContent`](../pdfcontent) 添加附件。 |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 备注

此集合包含 [`PdfAttachment`](../pdfattachment) 类型的项。

### 另请参阅

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfAttachment](../pdfattachment)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
