---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供用于设置 Presentation 文档预览生成的需求和流委托的选项。"
type: docs
weight: 2030
url: /zh/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/
---
## PresentationPreviewOptions class

提供用于设置 Presentation 文档预览生成的需求和流委托的选项。

```csharp
public class PresentationPreviewOptions : PreviewOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor)(CreatePageStream) | 初始化 [`PresentationPreviewOptions`](../presentationpreviewoptions) 类的新实例，导致输出流被关闭。 |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | 初始化 [`PresentationPreviewOptions`](../presentationpreviewoptions) 类的新实例，使输出流返回给客户端以供进一步使用。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | 获取或设置页面流创建委托的实例。 |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | 获取或设置页面预览高度。 |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | 获取或设置用于生成预览的页码数组。 |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | 获取或设置预览图像格式。 |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | 获取或设置页面预览完成委托的实例。 |
| [Resolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/resolution) { get; set; } | 获取或设置生成图像的分辨率（单位：每英寸点数）。 |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | 获取或设置页面预览宽度。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/defaultresolution) | 默认分辨率（每英寸点数）。 |

### 另请参阅

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
