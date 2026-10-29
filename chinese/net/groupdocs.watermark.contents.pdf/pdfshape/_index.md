---
title: "PdfShape"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供 XObjects 工件和注释的基类。"
type: docs
weight: 770
url: /zh/net/groupdocs.watermark.contents.pdf/pdfshape/
---
## PdfShape class

提供 XObjects、Artifacts 和 Annotations 的基类。

```csharp
public abstract class PdfShape : ShapeSearchAdapter, IRotatableTwoDObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [FormattedTextFragments](../../groupdocs.watermark.contents.pdf/pdfshape/formattedtextfragments) { get; } | 获取此 [`PdfShape`](../pdfshape) 的格式化文本片段集合。 |
| abstract [Height](../../groupdocs.watermark.contents.pdf/pdfshape/height) { get; } | 获取对象的高度。 |
| [Image](../../groupdocs.watermark.contents.pdf/pdfshape/image) { get; set; } | 获取或设置此 [`PdfShape`](../pdfshape) 的图像。 |
| abstract [RotateAngle](../../groupdocs.watermark.contents.pdf/pdfshape/rotateangle) { get; } | 获取对象的旋转角度（单位为度）。 |
| virtual [Text](../../groupdocs.watermark.contents.pdf/pdfshape/text) { get; set; } | 获取或设置此 [`PdfShape`](../pdfshape) 的文本。 |
| abstract [Width](../../groupdocs.watermark.contents.pdf/pdfshape/width) { get; } | 获取对象的宽度。 |
| abstract [X](../../groupdocs.watermark.contents.pdf/pdfshape/x) { get; } | 获取对象的 x 坐标。 |
| abstract [Y](../../groupdocs.watermark.contents.pdf/pdfshape/y) { get; } | 获取对象的 y 坐标。 |

### 另请参阅

* class [ShapeSearchAdapter](../../groupdocs.watermark.search/shapesearchadapter)
* interface [IRotatableTwoDObject](../../groupdocs.watermark.search/irotatabletwodobject)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
