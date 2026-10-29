---
title: "Search"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "搜索文档中所有可能的水印。"
type: docs
weight: 110
url: /zh/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

搜索文档中所有可能的水印。

```csharp
public PossibleWatermarkCollection Search()
```

### 返回值

可能的水印集合。

### 备注

搜索在 [`SearchableObjects`](../searchableobjects) 中指定的对象中进行。

了解有关搜索水印的更多信息 [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)。

### 示例

统计任何受支持类型文档中的可能水印。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### 另请参阅

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

根据指定的搜索条件搜索可能的水印。

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| searchCriteria | SearchCriteria | 要使用的搜索条件。 |

### 返回值

可能的水印集合。

### 备注

搜索在 [`SearchableObjects`](../searchableobjects) 中指定的对象中进行。

了解有关搜索水印的更多信息 [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)。

### 示例

查找并删除任何受支持类型文档中包含特定文本或图像的所有可能水印。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarks.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### 另请参阅

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
