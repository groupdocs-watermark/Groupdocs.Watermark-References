---
title: "VectorSearchCriteria"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示允许按水印颜色过滤的条件。"
type: docs
weight: 2760
url: /zh/net/groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/
---
## VectorSearchCriteria class

表示允许按水印颜色过滤的条件。

```csharp
public class VectorSearchCriteria : SearchCriteria
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VectorSearchCriteria](vectorsearchcriteria)() | 初始化 [`VectorSearchCriteria`](../vectorsearchcriteria) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [VectorColorRange](../../groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/vectorcolorrange) { get; set; } | 获取或设置用于按前景色过滤矢量水印的颜色范围。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | 使用逻辑 AND 运算符将此 [`SearchCriteria`](../searchcriteria) 与其他条件组合。 |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | 对该 [`SearchCriteria`](../searchcriteria) 取反。 |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | 使用逻辑 OR 运算符将此 [`SearchCriteria`](../searchcriteria) 与其他条件组合。 |

### 备注

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### 示例

使用搜索条件查找并移除水印。

```csharp
using (Watermarker watermarker = new Watermarker(@"C:\test.pdf"))
{
    VectorSearchCriteria searchCriteria = new VectorSearchCriteria();
    Color watermarkColor = ColorTranslator.FromHtml("#a9aaae");
    GroupDocs.Watermark.Watermarks.Color fromSystemColor = GroupDocs.Watermark.Watermarks.Color.FromArgb(watermarkColor.A, watermarkColor.R, watermarkColor.G, watermarkColor.B);
    ColorRange criteriaVectorColorRange = new ColorRange(fromSystemColor)
    {
       MinBrightness = 0.1f,
       MaxBrightness = 0.7f
    };
    searchCriteria.VectorColorRange = criteriaVectorColorRange;
    PossibleWatermarkCollection possibleWatermarkCollection = watermarker.Search(searchCriteria);
    possibleWatermarkCollection.Clear();
    watermarker.Save(@"C:\modified_test.pdf");
}
```

### 另请参阅

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
