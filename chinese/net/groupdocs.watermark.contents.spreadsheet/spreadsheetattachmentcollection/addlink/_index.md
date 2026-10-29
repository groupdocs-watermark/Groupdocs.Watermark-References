---
title: "AddLink"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "通过链接添加附件，文档中不包含附件文件内容。"
type: docs
weight: 20
url: /zh/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink/
---
## SpreadsheetAttachmentCollection.AddLink method

通过链接添加附件（文档将不包含附件文件内容）。

```csharp
public void AddLink(string sourceFullName, byte[] previewImageContent, double x, double y, 
    double width, double height)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| sourceFullName | String | 链接的文件路径。 |
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
