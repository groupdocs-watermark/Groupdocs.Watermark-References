---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供用于预览生成的需求设置和流委托的选项。"
type: docs
weight: 2140
url: /zh/net/groupdocs.watermark.options/previewoptions/
---
## PreviewOptions class

提供用于预览生成的需求设置和流委托的选项。

```csharp
public class PreviewOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | 初始化 [`PreviewOptions`](../previewoptions) 类的新实例，使输出流被关闭。 |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | 初始化 [`PreviewOptions`](../previewoptions) 类的新实例，使输出流返回给客户端以供进一步使用。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | 获取或设置页面流创建委托的实例。 |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | 获取或设置页面预览高度。 |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | 获取或设置用于生成预览的页码数组。 |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | 获取或设置预览图像格式。 |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | 获取或设置页面预览完成委托的实例。 |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | 获取或设置页面预览宽度。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
