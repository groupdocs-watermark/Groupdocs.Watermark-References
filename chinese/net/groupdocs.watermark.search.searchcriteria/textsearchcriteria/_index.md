---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示允许按水印文本过滤的条件。"
type: docs
weight: 2750
url: /zh/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

表示允许按水印文本过滤的条件。

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | 使用指定的正则表达式初始化 [`TextSearchCriteria`](../textsearchcriteria) 类的新实例。 |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | 使用搜索字符串初始化 [`TextSearchCriteria`](../textsearchcriteria) 类的新实例。 |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | 使用搜索字符串和比较标志初始化 [`TextSearchCriteria`](../textsearchcriteria) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | 获取或设置特定页码的列表 |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | 获取搜索模式。 |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | 获取或设置一个值，指示在字符串比较期间将跳过不可读字符。 |

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
using (Watermarker watermarker = new Watermarker(@"C:\test.some_ext"))
{
    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
    TextSearchCriteria textCriteria = new TextSearchCriteria(new Regex("^Test watermark$"));
    PossibleWatermarkCollection watermarks = watermarker.Search(textCriteria.And(widthRange.Or(rotateAngle)));
    watermarks.Clear();
    watermarker.Save();
}
```

### 另请参阅

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
