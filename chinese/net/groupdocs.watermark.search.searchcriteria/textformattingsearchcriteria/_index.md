---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示允许按文本格式过滤的条件。"
type: docs
weight: 2740
url: /zh/net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
---
## TextFormattingSearchCriteria class

表示允许按文本格式过滤的条件。

```csharp
public class TextFormattingSearchCriteria : SearchCriteria
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextFormattingSearchCriteria](textformattingsearchcriteria)() | 初始化 [`TextFormattingSearchCriteria`](../textformattingsearchcriteria) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/backgroundcolorrange) { get; set; } | 获取或设置用于按文本背景颜色过滤水印的颜色范围。 |
| [FontBold](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontbold) { get; set; } | 获取或设置一个值，以指示水印文本格式中使用的字体是否为粗体。 |
| [FontItalic](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontitalic) { get; set; } | 获取或设置一个值，以指示水印文本格式中使用的字体是否为斜体。 |
| [FontName](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontname) { get; set; } | 获取或设置用于可能的水印文本格式化的字体名称。 |
| [FontStrikeout](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontstrikeout) { get; set; } | 获取或设置一个值，指示用于水印文本格式化的字体是否为删除线。 |
| [FontUnderline](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontunderline) { get; set; } | 获取或设置一个值，指示用于水印文本格式化的字体是否为下划线。 |
| [ForegroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foregroundcolorrange) { get; set; } | 获取或设置用于按文本前景色过滤水印的颜色范围。 |
| [MaxFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/maxfontsize) { get; set; } | 获取或设置字体大小的结束值。 |
| [MinFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/minfontsize) { get; set; } | 获取或设置字体大小的起始值。 |

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

移除具有特定文本格式的可能水印（不论文档类型）。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.doc"))
{
    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
    criteria.ForegroundColorRange = new ColorRange();
    criteria.ForegroundColorRange.MinHue = -5;
    criteria.ForegroundColorRange.MaxHue = 10;
    criteria.ForegroundColorRange.MinBrightness = 0.01f;
    criteria.ForegroundColorRange.MaxBrightness = 0.99f;
    criteria.BackgroundColorRange = new ColorRange();
    criteria.BackgroundColorRange.IsEmpty = true;
    criteria.FontName = "Arial";
    criteria.MinFontSize = 19;
    criteria.MaxFontSize = 42;
    criteria.FontBold = true;

    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    watermarks.Clear();
    watermarker.Save();
}
```

### 另请参阅

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
