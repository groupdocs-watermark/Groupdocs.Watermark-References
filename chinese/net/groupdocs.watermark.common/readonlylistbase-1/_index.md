---
title: "ReadOnlyListBaseT"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供强类型 readonly 列表的抽象基类。"
type: docs
weight: 110
url: /zh/net/groupdocs.watermark.common/readonlylistbase-1/
---
## ReadOnlyListBase&lt;T&gt; class

提供强类型只读列表的抽象基类。

```csharp
public abstract class ReadOnlyListBase<T> : IList, IList<T>
```

| 参数 | 描述 |
| --- | --- |
| T | 元素的类型。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | 获取集合中包含的元素数量。 |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | 获取一个值，指示集合是否为只读。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | 获取集合中指定索引处的元素。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) | 确定集合是否包含特定项。 |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() | 返回遍历集合的枚举器。 |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) | 确定集合中特定项的索引。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
