---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示附加到 Excel 文档的文件。"
type: docs
weight: 1100
url: /zh/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

表示附加到 Excel 文档的文件。

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | 获取或设置与附件文件关联的描述性（替代）文本。 |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | 获取或设置附件文件内容。 |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | 获取或设置附件框架的高度（单位：点）。 |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | 获取一个值，指示内容是否仅包含指向文件的链接。 |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | 获取或设置附件文件的预览图像（字节数组）。 |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | 获取附件文件的完整名称。 |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | 获取或设置附件框架的宽度（单位：磅）。 |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | 获取或设置附件框架相对于工作表左边界的水平偏移量（单位：磅）。 |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | 获取或设置附件框架相对于工作表上边界的垂直偏移量（单位：磅）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | 从附件文件加载内容。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | 使用指定的加载选项从附件文件加载内容。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | 使用指定的加载选项和设置从附件文件加载内容。 |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | 获取存储在附件文件中的文档信息。 |

### 另请参阅

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
