---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示一个手动指定的图像区域，该区域应使用周围像素进行修复填充。"
type: docs
weight: 2900
url: /zh/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

表示应进行修复（使用周围像素填充）的手动指定图像区域。

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | 初始化一个新的 [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark) 类实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | 获取此 [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) 的格式化文本片段集合。 |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | 获取此 [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) 的高度。 |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | 获取或设置此 [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) 的图像。 |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | 获取或设置修复算法。默认值为 PatchBased。 |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | 获取放置水印的页面。 |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | 获取此 [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark) 的父对象。始终返回 `null`，因为该区域是手动指定的。 |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | 获取或设置算法使用的补丁大小（奇数，5-11）。默认值为 7。对于 Telea，此值用作 HalfPatchSize。 |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | 获取或设置要修复的多边形区域，单位为图像像素。每个多边形是顶点数组。必须指定 [`Rectangles`](./rectangles) 或 [`Polygons`](./polygons) 之一，但不能同时指定两者。 |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | 获取或设置要修复的矩形区域，单位为图像像素。必须指定 [`Rectangles`](./rectangles) 或 [`Polygons`](./polygons) 之一，但不能同时指定两者。 |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | 获取此 [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) 的旋转角度（单位：度）。 |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | 获取或设置此 [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) 的文本。 |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | 获取此 [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) 的计量单位。 |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | 获取此 [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) 的宽度。 |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | 获取此 [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) 的 X 坐标。 |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | 获取此 [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) 的 Y 坐标。 |

### 另请参阅

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
