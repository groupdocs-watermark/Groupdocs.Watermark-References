---
title: "SizingType"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "指定应如何计算水印大小。"
type: docs
weight: 3300
url: /zh/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

指定应如何计算水印大小。

```csharp
public enum SizingType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 水印应根据其内容自动调整大小。 |
| Absolute | `1` | 水印应精确设置为 [`Width`](../../groupdocs.watermark/watermark/width) 和 [`Height`](../../groupdocs.watermark/watermark/height) 的大小。 |
| ScaleToParentDimensions | `2` | 水印应使用指定的 [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) 相对于父级尺寸进行缩放。 |
| ScaleToParentArea | `3` | 水印应使用指定的 [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) 相对于父级区域进行缩放。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
