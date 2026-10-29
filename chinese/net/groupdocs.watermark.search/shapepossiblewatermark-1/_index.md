---
title: "ShapePossibleWatermarkT"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示任何受支持格式内容中的形状水印。"
type: docs
weight: 2770
url: /zh/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

表示任何受支持格式内容中的形状水印。

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| 参数 | 描述 |
| --- | --- |
| T | 形状的类型。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | 获取形状的格式化文本片段集合。 |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | 获取二维对象的高度。 |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | 获取或设置此 [`PossibleWatermark`](../possiblewatermark) 的图像。 |
| override [PageNumber](../../groupdocs.watermark.search/shapepossiblewatermark-1/pagenumber) { get; } | 获取放置水印的页面。 |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | 获取此 [`PossibleWatermark`](../possiblewatermark) 的父对象。 |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | 获取形状的旋转角度（单位：度）。 |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | 获取或设置形状的文本。 |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | 获取二维对象的计量单位。 |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | 获取二维对象的宽度。 |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | 获取二维对象的 X 坐标。 |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | 获取二维对象的 Y 坐标。 |

### 另请参阅

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
