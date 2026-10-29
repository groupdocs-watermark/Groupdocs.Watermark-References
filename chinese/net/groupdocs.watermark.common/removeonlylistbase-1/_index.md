---
title: "RemoveOnlyListBaseT"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供强类型 removeonly 列表的抽象基类。"
type: docs
weight: 130
url: /zh/net/groupdocs.watermark.common/removeonlylistbase-1/
---
## RemoveOnlyListBase&lt;T&gt; class

提供强类型仅删除列表的抽象基类。

```csharp
public abstract class RemoveOnlyListBase<T> : ReadOnlyListBase<T>
```

| 参数 | 描述 |
| --- | --- |
| T | 元素的类型。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | 获取集合中包含的元素数量。 |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | 获取一个值，指示集合是否为只读。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | 获取集合中指定索引处的元素。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() | 从集合中移除所有项。 |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(T) | 从集合中移除特定对象的第一次出现。 |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) | 移除指定索引处的项。 |

### 另请参阅

* class [ReadOnlyListBase&lt;T&gt;](../readonlylistbase-1)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
