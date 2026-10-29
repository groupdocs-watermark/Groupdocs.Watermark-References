---
title: "AddAttachment"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "向 SpreadsheetWorksheetgroupdocs.watermark.contents.spreadsheet/spreadsheetworksheet 添加附件。"
type: docs
weight: 10
url: /zh/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment/
---
## SpreadsheetAttachmentCollection.AddAttachment method

向 [`SpreadsheetWorksheet`](../../spreadsheetworksheet) 添加附件。

```csharp
public void AddAttachment(byte[] fileContent, string sourceFullName, byte[] previewImageContent, 
    double x, double y, double width, double height)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 文件内容 | 字节数组 | 要附加的文件内容。 |
| sourceFullName | String | 附件文件的完整名称（扩展名用于确定打开文件的合适应用程序）。 |
| previewImageContent | 字节数组 | 附件文件的预览图像，以字节数组形式表示。 |
| x | 双精度 | 附件框架的 x 坐标（单位为点）。 |
| y | 双精度 | 附件框架的 y 坐标（单位为点）。 |
| width | 双精度 | 附件框架的宽度（单位：点）。 |
| height | 双精度 | 附件框架的高度（单位：点）。 |

### 另请参阅

* class [SpreadsheetAttachmentCollection](../../spreadsheetattachmentcollection)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
