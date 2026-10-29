---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示用于在内容中查找图像的搜索条件。"
type: docs
weight: 2650
url: /zh/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

表示用于在内容中查找图像的搜索条件。

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | 使用指定的流初始化 [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) 类的新实例。 |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | 使用指定的文件路径初始化 [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | 获取或设置图像之间允许的最大差异。 |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | 获取或设置特定页码的列表 |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | 获取或设置缩略图大小。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | 使用逻辑 AND 运算符将此 [`SearchCriteria`](../searchcriteria) 与其他条件组合。 |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | 对该 [`SearchCriteria`](../searchcriteria) 取反。 |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | 使用逻辑 OR 运算符将此 [`SearchCriteria`](../searchcriteria) 与其他条件组合。 |

### 备注

此搜索条件使用二值化的图像缩略图来计算图像相似度。

### 另请参阅

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
