---
title: "内容"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示可以放置水印的内容。"
type: docs
weight: 150
url: /zh/net/groupdocs.watermark.contents/content/
---
## Content class

表示可以放置水印的内容。

```csharp
public abstract class Content : ContentPart, IDisposable
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 释放当前实例。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 另请参阅

* class [ContentPart](../contentpart)
* namespace [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
