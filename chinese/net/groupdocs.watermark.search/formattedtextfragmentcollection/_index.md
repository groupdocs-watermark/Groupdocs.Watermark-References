---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示可变的格式化文本片段集合。"
type: docs
weight: 2460
url: /zh/net/groupdocs.watermark.search/formattedtextfragmentcollection/
---
## FormattedTextFragmentCollection class

表示可变的格式化文本片段集合。

```csharp
public class FormattedTextFragmentCollection : RemoveOnlyListBase<FormattedTextFragment>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CollectionType](../../groupdocs.watermark.search/formattedtextfragmentcollection/collectiontype) { get; } | 获取格式化片段集合的类型。 |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | 获取集合中包含的元素数量。 |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | 获取一个值，指示集合是否为只读。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | 获取集合中指定索引处的元素。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add#add)(string) | 向集合添加格式化文本片段。 |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add#add_1)(string, Font) | 向集合添加格式化文本片段。 |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add#add_2)(string, Font, Color) | 向集合添加格式化文本片段。 |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add#add_3)(string, Font, Color, Color) | 向集合添加格式化文本片段。 |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(FormattedTextFragment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(FormattedTextFragment) |  |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert#insert)(int, string) | 在给定索引处将格式化文本片段插入集合。 |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert#insert_1)(int, string, Font) | 在给定索引处将格式化文本片段插入集合。 |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert#insert_2)(int, string, Font, Color) | 在给定索引处将格式化文本片段插入集合。 |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert#insert_3)(int, string, Font, Color, Color) | 在给定索引处将格式化文本片段插入集合。 |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(FormattedTextFragment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 备注

此集合包含 [`FormattedTextFragment`](../formattedtextfragment) 基础类型的项。

### 另请参阅

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [FormattedTextFragment](../formattedtextfragment)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
