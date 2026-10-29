---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供用于设置要求和流委托的选项，以生成 WordProcessing 文档的预览。"
type: docs
weight: 2360
url: /zh/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions class

提供用于设置要求和流委托的选项，以生成 WordProcessing 文档的预览。

```csharp
public class WordProcessingPreviewOptions : PreviewOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WordProcessingPreviewOptions](wordprocessingpreviewoptions#constructor)(CreatePageStream) | 初始化 [`WordProcessingPreviewOptions`](../wordprocessingpreviewoptions) 类的新实例，使输出流被关闭。 |
| [WordProcessingPreviewOptions](wordprocessingpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | 初始化 [`WordProcessingPreviewOptions`](../wordprocessingpreviewoptions) 类的新实例，使输出流返回给客户端以供进一步使用。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | 获取或设置页面流创建委托的实例。 |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | 获取或设置页面预览高度。 |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | 获取或设置用于生成预览的页码数组。 |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | 获取或设置预览图像格式。 |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | 获取或设置页面预览完成委托的实例。 |
| [Resolution](../../groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/resolution) { get; set; } | 获取或设置生成图像的分辨率（单位：每英寸点数）。 |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | 获取或设置页面预览宽度。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/defaultresolution) | 默认分辨率（每英寸点数）。 |

### 另请参阅

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
