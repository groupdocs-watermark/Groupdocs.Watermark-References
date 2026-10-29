---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示允许按水印旋转角度过滤的条件。"
type: docs
weight: 2710
url: /zh/net/groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/
---
## RotateAngleSearchCriteria class

表示允许按水印旋转角度过滤的条件。

```csharp
public class RotateAngleSearchCriteria : SearchCriteria
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RotateAngleSearchCriteria](rotateanglesearchcriteria)(double, double) | 使用起始角度和结束角度初始化 [`RotateAngleSearchCriteria`](../rotateanglesearchcriteria) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [MaximumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/maximumangle) { get; } | 获取以度为单位的结束角度。 |
| [MinimumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/minimumangle) { get; } | 获取以度为单位的起始角度。 |

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

使用搜索条件查找并删除水印。

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

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
