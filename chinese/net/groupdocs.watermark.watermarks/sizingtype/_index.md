---
title: SizingType
second_title: .NET API 参考的 GroupDocs.Watermark
description: 指定应如何计算水印大小
type: docs
weight: 3140
url: /zh/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

指定应如何计算水印大小。

```csharp
public enum SizingType
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 水印应根据其内容自动调整大小。 |
| Absolute | `1` | 水印的大小应精确到[`Width`](../../groupdocs.watermark/watermark/width)和[`Height`](../../groupdocs.watermark/watermark/height) |
| ScaleToParentDimensions | `2` | 水印应使用指定的 相对于父尺寸进行缩放[`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor). |
| ScaleToParentArea | `3` | 水印应使用指定的相对于父区域进行缩放[`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) |

### 也可以看看

* 命名空间 [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* 部件 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->