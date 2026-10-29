---
title: "TwoDObjectPossibleWatermark"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示任何受支持格式内容中的二维对象水印。"
type: docs
weight: 2790
url: /zh/net/groupdocs.watermark.search/twodobjectpossiblewatermark/
---
## TwoDObjectPossibleWatermark class

表示任何受支持格式内容中的二维对象水印。

```csharp
public abstract class TwoDObjectPossibleWatermark : PossibleWatermark
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | 获取此 [`PossibleWatermark`](../possiblewatermark) 的格式化文本片段集合。 |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | 获取二维对象的高度。 |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | 获取或设置此 [`PossibleWatermark`](../possiblewatermark) 的图像。 |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | 获取放置水印的页面。 |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | 获取此 [`PossibleWatermark`](../possiblewatermark) 的父对象。 |
| override [RotateAngle](../../groupdocs.watermark.search/twodobjectpossiblewatermark/rotateangle) { get; } | 获取 2D 对象的旋转角度（单位：度）。 |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | 获取或设置此 [`PossibleWatermark`](../possiblewatermark) 的文本。 |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | 获取二维对象的计量单位。 |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | 获取二维对象的宽度。 |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | 获取二维对象的 X 坐标。 |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | 获取二维对象的 Y 坐标。 |

### 另请参阅

* class [PossibleWatermark](../possiblewatermark)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
