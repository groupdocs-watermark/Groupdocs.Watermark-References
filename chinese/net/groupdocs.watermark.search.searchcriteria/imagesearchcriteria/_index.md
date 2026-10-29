---
title: "ImageSearchCriteria"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供图像搜索条件的基类。"
type: docs
weight: 2640
url: /zh/net/groupdocs.watermark.search.searchcriteria/imagesearchcriteria/
---
## ImageSearchCriteria class

提供图像搜索条件的基类。

```csharp
public abstract class ImageSearchCriteria : PageSearchCriteria
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | 获取或设置图像之间允许的最大差异。 |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | 获取或设置特定页码的列表 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | 使用逻辑 AND 运算符将此 [`SearchCriteria`](../searchcriteria) 与其他条件组合。 |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | 对该 [`SearchCriteria`](../searchcriteria) 取反。 |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | 使用逻辑 OR 运算符将此 [`SearchCriteria`](../searchcriteria) 与其他条件组合。 |

### 另请参阅

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
