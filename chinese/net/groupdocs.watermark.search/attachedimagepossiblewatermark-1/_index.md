---
title: "AttachedImagePossibleWatermarkT"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示附加在任何受支持格式内容中的图像水印。"
type: docs
weight: 2430
url: /zh/net/groupdocs.watermark.search/attachedimagepossiblewatermark-1/
---
## AttachedImagePossibleWatermark&lt;T&gt; class

表示附加在任何受支持格式内容中的图像水印。

```csharp
public abstract class AttachedImagePossibleWatermark<T> : PossibleWatermark
    where T : Attachment
```

| 参数 | 描述 |
| --- | --- |
| T | 附件的类型。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | 获取此 [`PossibleWatermark`](../possiblewatermark) 的格式化文本片段集合。 |
| override [Height](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/height) { get; } | 获取此 [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) 的高度。 |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | 获取或设置此 [`PossibleWatermark`](../possiblewatermark) 的图像。 |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | 获取放置水印的页面。 |
| override [Parent](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/parent) { get; } | 获取此 [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) 的父对象。 |
| override [RotateAngle](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/rotateangle) { get; } | 获取此 [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) 的旋转角度（单位：度）。 |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | 获取或设置此 [`PossibleWatermark`](../possiblewatermark) 的文本。 |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/unitofmeasurement) { get; } | 获取此 [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) 的计量单位。 |
| override [Width](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/width) { get; } | 获取此 [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) 的宽度。 |
| override [X](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/x) { get; } | 获取此 [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) 的 X 坐标。 |
| override [Y](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/y) { get; } | 获取此 [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) 的 Y 坐标。 |

### 另请参阅

* class [PossibleWatermark](../possiblewatermark)
* class [Attachment](../../groupdocs.watermark.common/attachment)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
