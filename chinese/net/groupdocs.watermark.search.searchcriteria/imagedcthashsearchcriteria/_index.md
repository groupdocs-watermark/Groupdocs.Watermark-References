---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示用于在文档中查找图像的搜索条件。"
type: docs
weight: 2630
url: /zh/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

表示用于在文档中查找图像的搜索条件。

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | 使用指定的流初始化一个新的 [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) 类实例。 |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | 使用指定的文件路径初始化一个新的 [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) 类实例。 |

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

### 备注

此搜索条件使用基于 DCT 的感知图像哈希来计算图像相似度。**了解更多：**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### 示例

在附件文件（pdf）中搜索图像。

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // 指定用于比较文档图像的示例图像
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // 搜索相似图像
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // 删除或修改已发现的图像水印
    // ...
}
```

### 另请参阅

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
