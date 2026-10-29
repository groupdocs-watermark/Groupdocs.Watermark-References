---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示用于在内容中查找图像的搜索条件。"
type: docs
weight: 2620
url: /zh/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

表示用于在内容中查找图像的搜索条件。

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | 使用指定的流初始化 [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) 类的新实例。 |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | 使用指定的文件路径初始化 [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | 获取或设置用于构建颜色直方图的箱数量。 |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | 获取或设置图像之间允许的最大差异。 |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | 获取或设置特定页码的列表 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | 使用逻辑 AND 运算符将此 [`SearchCriteria`](../searchcriteria) 与其他条件组合。 |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | 对该 [`SearchCriteria`](../searchcriteria) 取反。 |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | 使用逻辑 OR 运算符将此 [`SearchCriteria`](../searchcriteria) 与其他条件组合。 |

### 备注

此搜索条件使用图像颜色直方图来计算图像相似度。

### 另请参阅

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
