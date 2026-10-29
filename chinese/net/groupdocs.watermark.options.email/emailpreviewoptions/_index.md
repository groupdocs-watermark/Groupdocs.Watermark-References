---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供用于设置要求和流委托以生成电子邮件文档预览的选项。"
type: docs
weight: 1780
url: /zh/net/groupdocs.watermark.options.email/emailpreviewoptions/
---
## EmailPreviewOptions class

提供用于设置要求和流委托以生成电子邮件文档预览的选项。

```csharp
public class EmailPreviewOptions : PreviewOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmailPreviewOptions](emailpreviewoptions#constructor)(CreatePageStream) | 初始化 [`EmailPreviewOptions`](../emailpreviewoptions) 类的新实例，使输出流被关闭。 |
| [EmailPreviewOptions](emailpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | 初始化 [`EmailPreviewOptions`](../emailpreviewoptions) 类的新实例，使输出流返回给客户端以供进一步使用。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | 获取或设置页面流创建委托的实例。 |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | 获取或设置页面预览高度。 |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | 获取或设置用于生成预览的页码数组。 |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | 获取或设置预览图像格式。 |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | 获取或设置页面预览完成委托的实例。 |
| [Resolution](../../groupdocs.watermark.options.email/emailpreviewoptions/resolution) { get; set; } | 获取或设置生成图像的分辨率（单位：每英寸点数）。 |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | 获取或设置页面预览宽度。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.email/emailpreviewoptions/defaultresolution) | 默认分辨率（每英寸点数）。 |

### 另请参阅

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
