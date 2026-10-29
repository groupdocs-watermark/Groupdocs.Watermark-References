---
title: "PdfXObject"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示 PDF 文档中的 XObject。"
type: docs
weight: 830
url: /zh/net/groupdocs.watermark.contents.pdf/pdfxobject/
---
## PdfXObject class

表示 PDF 文档中的 XObject。

```csharp
public abstract class PdfXObject : PdfShape
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [FormattedTextFragments](../../groupdocs.watermark.contents.pdf/pdfshape/formattedtextfragments) { get; } | 获取此 [`PdfShape`](../pdfshape) 的格式化文本片段集合。 |
| override [Height](../../groupdocs.watermark.contents.pdf/pdfxobject/height) { get; } | 获取此[`PdfXObject`](../pdfxobject)的高度（单位为点）。 |
| [Image](../../groupdocs.watermark.contents.pdf/pdfshape/image) { get; set; } | 获取或设置此 [`PdfShape`](../pdfshape) 的图像。 |
| [Page](../../groupdocs.watermark.contents.pdf/pdfxobject/page) { get; } | 获取此[`PdfXObject`](../pdfxobject)的父页面。 |
| override [RotateAngle](../../groupdocs.watermark.contents.pdf/pdfxobject/rotateangle) { get; } | 获取此[`PdfXObject`](../pdfxobject)的旋转角度（单位为度）。 |
| virtual [Text](../../groupdocs.watermark.contents.pdf/pdfshape/text) { get; set; } | 获取或设置此 [`PdfShape`](../pdfshape) 的文本。 |
| override [Width](../../groupdocs.watermark.contents.pdf/pdfxobject/width) { get; } | 获取此[`PdfXObject`](../pdfxobject)的宽度（单位为点）。 |
| override [X](../../groupdocs.watermark.contents.pdf/pdfxobject/x) { get; } | 获取此[`PdfXObject`](../pdfxobject)相对于页面左边界的水平偏移（单位为点）。 |
| override [Y](../../groupdocs.watermark.contents.pdf/pdfxobject/y) { get; } | 获取此[`PdfXObject`](../pdfxobject)相对于页面底部边界的垂直偏移（单位为点）。 |

### 备注

**Learn more**

* [Working with XObjects](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

### 另请参阅

* class [PdfShape](../pdfshape)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
